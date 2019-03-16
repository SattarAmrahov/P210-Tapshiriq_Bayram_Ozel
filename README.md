# Tapshiriq 1 - Bootstrap Template:

Bootstrap Template folder-indeki template.png shekline uygun website hazirlayin. 
Saytdaki effektlerin nece olacagina baxmaq ucun Google Drive-da P210 ile share olunmush P210 Videos folderindeki Novruz_bootstrap_template.mp4 videosuna baxin.

Bootstrap istifade edin. Hazirladiginiz website telefon, planshet ve komputer ekranlarina uygun shekilde responsive olsun.

Istifade etmek ucun shekil tapmaqda cetinlik cekseniz ashagidaki saytlardan istifade ede bilersizin:
- https://unsplash.com/
- https://pixabay.com/



# Tapshiriq 2 - Todo List:

Todo List folderindeki todo.png shekline uygun web application hazirlayin.

- Shekildeki dizaynda oldugu kimi, ashagidaki input-a yeni tapshiriq daxil edib "+ New Task" button-una click etdikde melumat siyahiya elave olunsun. 

- Siyahidaki item-lardan her hansinin uzerine click etdikde uzerinden xett cekilsin (shekildeki kimi), eger xett cekilmish item-a click olunarsa normal veziyyete qayitsin. 

- Siyahidaki item-larin uzerine geldikde uygun item-in kenarinda silmek ucun delete icon-u gorunsun (shekildeki kimi). 

- Delete icon-una click etdikde hemin item siyahidan silinsin

- Siyahida 5-den cox item olduqda ashagi ve yuxari hereket etdirmek ucun scroll yaransin

Qeyd: Tapshiriq 2-de hover ve diger effectler ucun JavaScript istifade edin. CSS ile yalnizca umumi dizayni hazirlayin


# Tapshiriq 3 - JS Objects:

JS Objects folderindeki JS_Objects_Task_v1.1.png shekline uygun web application hazirlayin.

6 eded Object yaratmalisiniz. Bunlar ashagidakilardir:
 1. Academy
    - Properties:
        - name : string
        - address : Address object
        - students : Array of Student objects
        - teachers : Array of Teacher objects
        - rooms : Array of Room objects
        - groups : Array of Group objects
    - Methods:
        - addStudent()
        - addTeacher()
        - addRoom()
        - addGroup()
 2. Student
    - Properties:
        - id : number
        - name : string
        - surname : string
        - email : string
        - address : Address object
    - Methods:
        - username() : name + surname
 3. Address
    - Properties:
        - street : string
        - city : string
        - country : string
 4. Room
    - Properties:
        - id : number
        - name : string
        - capacity : number
 5. Group
    - Properties:
        - id : number
        - name : string
        - room : Room object
 6. Teacher
    - Properties:
        - id : number
        - name : string
        - surname : string
        - email : string
        - groups : Array of Group objects
    - Methods:
        - addGroup()


Application yuklenen zaman yeni bir Academy object-i yaradin. Menim numunemde "Code Academy" istifade edilib. Yaratdiginiz academy-nin adini ve addressini js faylinda objecti yaradan zaman menimsedin. 

Meselen:

    let academyAddress = new Address("Nizami street", "Baku", "Azerbaijan"); 
    let myAcademy = new Academy("Code Academy", academyAddress);

Applicationun geride qalan hissesi Drive-da share elediyim Novruz_JS_Objects .mp4 videosundaki kimi olmalidir.

