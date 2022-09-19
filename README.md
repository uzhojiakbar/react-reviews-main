# Git Hub ga kirish!
### Git nima?
    Git vaqt otishi bilan o'zgarishlarni yozib olishga imkon beradigan tizim

### Github nima
    Github - online store
    Git repozitoriylarini boshqarishga imkon beradigan bulutga asoslangan hosting xizmati.
    oddiy qilib aytanda malumot tarqatish uchun, fleshkadan avzal tomini biz masalan sheriklarim nimani qachon qanday ozgartirganini bila olamiz. Fleshkani qolimizdan kotarib yurmaymizda, online strore (xotira) ga joylab qoyish orqali istalgan payt malumot ola olamiz.

### Branch -  Online store
    Masalan bir proect ustida 10kishi ishlamoqda, har bir odam telegramdan yoki fleshkadan malumotni bir biriga otkazish juda noqulay, online store orqali malumotni bu narsa juda qulay, online storeda shu proect dagi har bir kishi bir biriga malumotni oson tarzda otkazishi mumkin. Masalan bir kishi kodni store ga yuborsa u qolgan 9 kishida ham korinadi va uni osongina qayta ishlata oladi, bir kishi malumot ochirsa u hammadan ochadi
### Brench 
    Katta proectlarda ishlanyotganda Har bir dasturchiga bitadan brench ochiladi
    yani masalan men navbar ni yasayapman, menga bir brench ochialdi va men codelarni
    shu yerga push qilaman, agarda masterga push  qilsam kotta proect buzilishi mumkin

### Branch yaratish va unga otish
#### `git branch BrenchName`  
    BrenchName nomli branch ochiladi
#### `git checkout BrenchName`
    Men hozir ozim turgan branch dan `BrenchName` nomli branch ga otib olaman

### git repository ochish va vs code ga ulash
    repository larga papka sifatida  qarasak boladi (.git fayllari),
    Har bir proect uchun 1 repository ochiladi,
    Buning uchun github.com ga otamiz va + iconcasi ustiga bosib repository nomini yozamiz va yaratamiz.
### `git init`
    git init qiladigan bolsak bizga bita .git fayli yaratiladi
    git remote add origin "github.com/username/exemle.git"
    bu yerda origin sozini istalgan sozga ozgartirsak boladi. bunday holda push     pull da      ham shu soz kiritladi, men hozirda origin ni kiritaman
    "" - ichidagi manzilda repo manzili kiritiladi, guthubdan yaratgan repoga kirs  tepada         kiritilgan boladi, yoki code ni ustiga bossak shu yerda tura   copy qilib kiritamiz

#### `git add`
    `git add .`
    git add - barcha fayllarni kuzatadi, agar tepadagi commandni kitiadigan bo'lsak oldingi pushdan keyin nima bolgan qanday ozgarish, nima yaratilgan va nima ozgarganini oqiydi, va uni xotiraga oladi
    git add . - bu yerda (.) ni o`rniga faylnomi ham kritish mumkin, shunda faqat kiritilgan nomdagi xotiraga oladi
#### `git commit -m "Your Description"`
    Git commit nimani anglatadi? Git commit buyrug'i loyihaning hozirda bosqichma-bosqich o'zgarishlarining suratini oladi. Taqdim etilgan suratlarni loyihaning "xavfsiz" versiyalari deb hisoblash mumkin
    -m "Your massage" - bu yerda siz qanday ozgarshlar bolganini qisqa va tushunarli qilib joatishingiz kere boaldi.

#### `Git push nima qiladi`
    `git push origin master`
    git push -  git add qilgan malumotlarni github ga qoshadi, eski malumotlar yangilanib, git add qilgandegi malumotlar joylanadi
    origin - bu yerda remote manzili
    master - branch nomi

### `Git pull origin master`
    Git Pull - biror bir brachda hozirgi turgan branchingizga malumot olish
    origin - remote nomi
    master - branch nomi

