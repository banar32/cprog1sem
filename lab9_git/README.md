# Практическое задание 9. Git
## Оценка 3:
**1,2:**
<img width="1702" height="454" alt="изображение" src="https://github.com/user-attachments/assets/c7022e92-85d5-4715-bceb-d9838288ea5f" />
**Увидели что находимся в ветке main, а также ознакомились с тем, как выглядит git log**  
**3,4:**
<img width="1641" height="445" alt="изображение" src="https://github.com/user-attachments/assets/2ddffd5a-541d-413e-9a17-76894782672a" />
**Создали файл sort.c и добавили туда функцию сортировки bubble sort, после вывода git status заметим, что файл sort.c отображается как неотслеживаемый**  
**5,6:**
<img width="1521" height="345" alt="изображение" src="https://github.com/user-attachments/assets/6ffbd54a-3814-4a71-906c-1981b0d0941c" />
**Добавили файл sort.c в stage, использовав git status убедимся что sort.c готов к коммиту**  
**7,8:**
<img width="1408" height="399" alt="изображение" src="https://github.com/user-attachments/assets/5fa41b6d-fbd2-4295-993d-07b4d90d5a0a" />
**Закоммитили файл sort.c, использовав git status убедились что больше нечего коммитить и наша ветка опережает ветку origin/main на 1 коммит.**  
**9,10:**
<img width="1638" height="436" alt="изображение" src="https://github.com/user-attachments/assets/ab80c490-b8a2-4272-a51f-062a4aa31f1a" />
**После добавления комментария видем что статус файла sort.c поменялся на: изменено, но не готово к коммиту т.к горит красным**  
**11,12:**
<img width="1638" height="436" alt="изображение" src="https://github.com/user-attachments/assets/444c5572-0c64-44bd-80ec-78ff8c8efe64" />
**Добалили изменённый файл sort.c в stage**  
**13,14:**
<img width="989" height="206" alt="изображение" src="https://github.com/user-attachments/assets/25f08972-4f70-4cc5-8a1e-9e56a62e0f13" />
**Добавили комментарий и сделали коммит**  
**15:**
<img width="918" height="136" alt="изображение" src="https://github.com/user-attachments/assets/57511220-194a-4c32-826c-6863cc41904f" />
<img width="1425" height="655" alt="изображение" src="https://github.com/user-attachments/assets/8b0db76a-2f47-4041-9e37-c0f4062c2108" />
**Заметим, что теперь опережаем на 2 коммита, а значит закоммитился предпоследний комментарий, а последний ещё даже не в stage**  
**16,17**
<img width="1431" height="914" alt="изображение" src="https://github.com/user-attachments/assets/20449a84-db3d-4439-a0b9-f3c02b3c82ea" />
**Добавили в stage, закоммитили, а также отправили изменения на удалённый репозиторий**
### Ветки:
**1,2:**  
<img width="543" height="169" alt="изображение" src="https://github.com/user-attachments/assets/23f39d4b-ca34-4058-a600-97956b76bded" />  
**Создали ветку mybranch,активной до сих пор является main**   
**3,4,5:**
<img width="978" height="327" alt="изображение" src="https://github.com/user-attachments/assets/9cee14c4-61be-4bb0-94c8-7b63cb5c698e" />  
**Сделали ветку mybranch активной, затем убедились в этом**  
**6,7:**
<img width="1522" height="240" alt="изображение" src="https://github.com/user-attachments/assets/2389a71e-46c9-49fb-9237-ca9c01e2dcbc" /> 
**Создали файл куда добавили свой никнейн и закомитили его**  
**8,9,10:**
<img width="1604" height="654" alt="изображение" src="https://github.com/user-attachments/assets/1d7aee37-f702-49c0-9888-6dd08d00c851" /> 
**Убедились что ветка указывает на новый коммит, затем переключились на ветку main и заметили что коммит из ветки mybranch не отображается**
**11:**
<img width="938" height="250" alt="изображение" src="https://github.com/user-attachments/assets/fea5de54-fc29-46e7-8922-b902788a440e" />
**Создали и закоммитили file2.txt**  
**12:**
<img width="1510" height="372" alt="изображение" src="https://github.com/user-attachments/assets/0e7ab795-eb92-49b7-8435-5d035268cb14" />
**Заметим, что у двух наших веток разные коммиты**  
**13,14,15:**
<img width="1086" height="609" alt="изображение" src="https://github.com/user-attachments/assets/eeb108f2-9ea3-4d75-a86d-e6d80088ea49" /> 
**После смены ветки на mybranch, заметим что файла file2.txt не отображается в данной ветке, затем с помощью команды gitdif увидим разницу в ветках**  
**16,17:**
<img width="1313" height="893" alt="изображение" src="https://github.com/user-attachments/assets/22fc50b6-ad66-4bab-9516-24bccab3b85f" />  
<img width="564" height="229" alt="изображение" src="https://github.com/user-attachments/assets/4730e347-01c9-4ce6-9519-aa91ad6d4c3a" />  
**добавили README.MD в ветку mybranch, а также закоммитили и запушили её на удалённый репозиторий, затем убедились что всё на месте**
## Оценка 4:  
**1,2:**  
<img width="839" height="631" alt="изображение" src="https://github.com/user-attachments/assets/ab6f9049-37a0-494f-9866-2105dff86c33" />  
**Дописали bubblesort и с помощью git diff увидели чтобыло добавлено**  
**3,4,5,6,7:**  
<img width="843" height="715" alt="изображение" src="https://github.com/user-attachments/assets/116462c5-b976-4e84-84e5-55324d571001" />  
**Увидем что после добавления в stage, git diff не видит что мы добавили в последний раз, он сравнивает файл с файлом в стейдже, а мы уже добавили туда изменённый файл
sort.c, поэтому написав git diff --staged уже сравнили добавленный sort.c в stage с его последним коммитом и вывелись различия**   
**8,9,10,11,12:**  
<img width="867" height="554" alt="изображение" src="https://github.com/user-attachments/assets/64c220dd-48ce-494a-a6f2-bf70c7f0607f" />  
<img width="842" height="685" alt="изображение" src="https://github.com/user-attachments/assets/b5b90c33-5844-4ee6-9b40-1b11d7a42081" />  
<img width="1367" height="434" alt="изображение" src="https://github.com/user-attachments/assets/81e073b4-daa2-4084-8625-380974dc3eef" />
**После изменения файла при вызове git diff он сравнится с файлом который добавлен последним в stage, а при git diff --stage также сравнивается то что, лежит в stage с
последним коммитом, в git status выводится 2 варианта, 1 закоммитить тот что лежит в stage, либо добавить в stage Изменённый вариант и потом закоммитить**  
**13,14:**  
<img width="1370" height="384" alt="изображение" src="https://github.com/user-attachments/assets/d2748daf-f78a-43d6-8437-422f600056ce" />  
**Грубо говоря убрали версию файла sort.c которую добавляли в stage, поэтому теперь он не отображается как готовый к коммиту**  
**15,16:**  
<img width="872" height="149" alt="изображение" src="https://github.com/user-attachments/assets/85aa3066-9a64-4c2f-bf5c-065f714bc55e" />  
<img width="1529" height="218" alt="изображение" src="https://github.com/user-attachments/assets/660f54bb-cd3c-4bf8-8a63-63c483445ea5" />
**После коммита заметим что, в журнале показывается что мы сделали коммит**  
**17,18,19**:
<img width="1364" height="1105" alt="изображение" src="https://github.com/user-attachments/assets/a7b4771e-a5f9-48e5-a073-1be64a02cce7" />  
**После вывода с cat видем что файл с изменениями, git status показывает что файл неиндексирован**  
**20,21,22:**  
<img width="459" height="51" alt="изображение" src="https://github.com/user-attachments/assets/68496333-76dc-46e3-ba42-0bae421d9a72" />  
<img width="743" height="696" alt="изображение" src="https://github.com/user-attachments/assets/5b9cd051-306b-4e2a-80d5-87ee0b865aa4" />  
<img width="1141" height="221" alt="изображение" src="https://github.com/user-attachments/assets/039fd443-ee3f-4cb1-8cc0-b46765b6174c" />  
**Отменили последние изменения файла, теперь в sort.c последний коммит"**  
**23:**
<img width="1123" height="347" alt="изображение" src="https://github.com/user-attachments/assets/974b2382-e322-43f4-847a-c917817cccc6" />
**Запушили**  
# Ветки и ff-merge  
**1,2:**:
<img width="837" height="212" alt="изображение" src="https://github.com/user-attachments/assets/d65e303c-2dc5-4033-8e0a-8030bf346152" />  
<img width="833" height="127" alt="изображение" src="https://github.com/user-attachments/assets/55a08010-eb01-4af4-a49b-f5fc3d4d129e" />  
**Создали файл greeting и закоммитили его, затем добавили туда hello и снова закоммитили**  
**3,4,5:**  
<img width="817" height="207" alt="изображение" src="https://github.com/user-attachments/assets/d71daee7-b69e-43e9-9763-cc34947fcbf0" />
**Создали новую ветку, переключились на неё, git status показал что изменений нет, логично ведь внутри неё не делали ни одного коммита**  
**6,7,8,9:**  
<img width="1137" height="271" alt="изображение" src="https://github.com/user-attachments/assets/aa8a7b8a-5c81-46df-9f65-8b04e4ccf49b" />  
<img width="1291" height="140" alt="изображение" src="https://github.com/user-attachments/assets/36568b78-386c-43cf-8f0d-3b7312f1fe08" />  
**Отредактировали файл greeting и закоммитили его, затем c git branch убедились что находимся в новой ветке, с помощью git log увидели, что
функция что последний коммит ушёл на 1 коммит вперёд относительно main**  
**10,11,12:**  
<img width="1126" height="492" alt="изображение" src="https://github.com/user-attachments/assets/e268922a-3c2d-4ae4-a6f0-8f063d879a71" />
**Переключились на ветку main, там вывели сначала сам файл а потом посмотрели разницу с файлом, который коммитили в ветке feature/uppercase** 
**13,14,15:**  
<img width="756" height="211" alt="изображение" src="https://github.com/user-attachments/assets/8b50a348-375c-49c2-977e-bc4e9bc23011" />  
<img width="828" height="74" alt="изображение" src="https://github.com/user-attachments/assets/473354df-c87b-4214-bb23-ca790b2d91ce" />  
**Смёржили ветку feature/uppercase В main, вывели содержимое и убедились что в файле greeting HELLO с последнего коммита ветки feature/uppercase, затем
удалили ветку feature/uppercase**  
**16,17,18:**  
<img width="1797" height="211" alt="изображение" src="https://github.com/user-attachments/assets/5f9fa8e2-2632-4904-afa1-05fb84a442c7" />  
<img width="1119" height="247" alt="изображение" src="https://github.com/user-attachments/assets/3d4b6a1c-9d94-4634-8819-1c05739503a2" />
**Смержили mybranch в main, видим что произошёл мерж-коммит так как ветки разошлись поэтому фаст-форвард невозможен**  



















































