<h1>WEATHER APPLICATION</h1>

<p style='text-align:  justify;'> 
    <span style='margin-left: 40px;'>Цей</span> 
    проєкт розроблено з метою ознайомлення із роботою 
    <a href='https://developer.mozilla.org/en-US/docs/Glossary/API'>API</a>, 
    принципом отримання даних від віддаленого серверу, вмінням обробляти дані, структурувати та застосовувати у свому проєкті. А саме застосовувалось API такого веб-ресурсу як 
    <a href='https://openweathermap.org/'>OpenWeatherMap</a>.
    Проєкт допоможе розібратисяс у роботі файлів
    <a href='https://www.json.org/json-uk.html'>JSON</a>, 
    як правильно отримувати та зберігати дані у файлах з типом json. Та познайомить користувача з інтерфейсом застосунку розробленим за допомогою пакету 
    <a href='https://customtkinter.tomschimansky.com/'>Custotkinter</a>.
</p>

<img src='/static/icon/screen.png'>

<h2>Зміст:</h2>
<ol>
    <li>
        <a href='#all-modules'>Модулі проєкту</a>.
    </li>
    <li>
        <a href='#download-project'>Розгортання проєкту</a>.
    </li>
    <li>
        <a href='#create-venv'>Створення віртуального оточення</a>.
        <ul>
            <li>
                <a href='#windows'>Для Windows</a>.
            </li>
            <li>
                <a href='#mac-os'>Для Mac OS</a>.
            </li>
        </ul>
    </li>
    <li>
        <a href='#download-modules'>Завантаження модулей до віртуального проєкту</a>.
        <ul>
            <li>
                <a href='#requriments'>Завантаження requriments.txt</a>.
            </li>
            <li>
                <a href='#pip-install'>Завантаження окремих модулів</a>.
            </li>
        </ul>
    </li>
    <li>
        <a href='#start-project'>Старт проєкту</a>.
    </li>
    <li>
        <a href='#base-mechanics'>Основні механіки проєкту</a>.
    </li>
    <li>
        <a href='#result'>Висновок</a>.
    </li>
</ol>

<hr>
У цьому розділі наведено повний зміст документації, що дозволить швидко ознайомитись із усіма етапами роботи над проєктом, та зрозуміти що та як використовував автор.


<hr>
<h3 id='all-modules'>Модулі проєкту</h3>

У проєкті використовуються такі модулі:

- `requests` - для надсилання HTTP-запитів до API OpenWeatherMap
- `json` - для обробки отриманих даних у форматі JSON
- `customtkinter` - для створення графічного інтерфейсу користувача
- `datetime` - для роботи з датою та часом
- `os` - для роботи з файлами
- `customtkinter` - для роботи з інтерфейсом застосунку
- `gui` - для роботи з графічним інтерфейсом користувача
- `Pillow` - для роботи з зображеннями 



<h3 id='download-project'>Розгортання проєкту</h3>

<p>
    Щоб проєкт гарно працював на вашому комп’ютері, необхідно дотримуватись наступних кроків: створити віртуальне середовище, завантажити залежності та запустити застосунок.
</p>

<h4 id='system-requirements'>Вимоги до системи</h4>
<ul>
    <li>Python версії 3.8 або вище</li>
    <li>Операційна система: Windows, MacOS або Linux</li>
    <li>Інтернет-з'єднання для роботи з API OpenWeatherMap</li>
</ul>

<h3 id='create-venv'>Створення віртуального оточення</h3>

<h4 id='windows'>Для Windows</h4>
<pre><code>python -m venv venv
venv\Scripts\activate</code></pre>

<h4 id='mac-os'>Для Mac OS / Linux</h4>
<pre><code>python3 -m venv venv
source venv/bin/activate</code></pre>

<h3 id='download-modules'>Завантаження модулей до віртуального проєкту</h3>

<h4 id='requriments'>Завантаження requirements.txt</h4>
<pre><code>pip install -r requirements.txt</code></pre>

<h4 id='pip-install'>Завантаження окремих модулів</h4>
<pre><code>pip install requests customtkinter Pillow</code></pre>
<p>Інші модулі входять до стандартної бібліотеки Python, тому додатково не встановлюються.</p>

<h3 id='start-project'>Старт проєкту</h3>

<p>Після встановлення всіх модулів та налаштування API ключа, запустіть головний файл:</p>
<pre><code>python main.py</code></pre>

<p>Після запуску відкриється графічний інтерфейс, у якому можна переглядати актуальну погоду у вказаному місті.</p>

<h4>Можливі проблеми:</h4>
<ul>
    <li>Перевірте, чи активоване віртуальне середовище</li>
    <li>Переконайтесь, що API ключ є дійсним</li>
</ul>
