   // 3.  Створіть змінні a6, a7, a8, a9, a10. Запишіть в них результати виразів:
    //     5 % 3,   2
    //     3 % 5,   5
    //     5 + '3', '53'
    //     '5' - 3,  2
    //     75 + 'кг' '75кг'
    // let a6, a7, a8, a9, a10;
// ++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
    {
        // Напишіть код, який вирахує прямокутник висотою 23см змінна хейгхт, та шириною 10 см.
        // Значення зберігти в змінній S

        let height = 23;
        let width = 10;
        let res = width * height;

        console.log(res);
    }

    // ++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

    // Напишіть код який виводить об"єм циліндра висотою 10м хейгзтС та діаметром основи 4м ДиСи" +
    // "Результат запишіть у V"

        let heightC = 10;
        let dC = 4;
        let radius = dC / 2;
        let P = 3.14;
        let V = P * radius * radius * heightC;
        console.log(V);
// В прямокутного трикутника дві сторони n зі значеннями 3 та m зі значенням 4
// Знайдіть гіпотенузу К по теоремі Піфагора (використати функциію math.pow) (число степінь),
//     або оператор возведення в степінь

    // let n = 3;
    // let m = 4;
    let number = Math.sqrt(Math.pow(3,2)+Math.pow(4,2));
    console.log(number);

    // Вивести у вікно браузера за допомогою метода alert наступні дані:
    // ПІБ, вік, хоббі (кожен з нової строки за допомогою \n)

    let name = 'Pavlo';
    let surname = 'Kraynikov';
    let age = 38;
    let hobby = 'aviamodelism';

    alert('MY NAME: ' + name + ' ' +surname );
    alert('I am: ' + age + ' my hobbys: '+ hobby);

    document.write(name + <br> + surname)
