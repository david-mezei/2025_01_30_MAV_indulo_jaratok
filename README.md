## MÁV utastájékoztató

Ez a projekt egy egyszerű lehetőséget biztosít ahhoz, hogy információkat tudjunk meg a vonatok indulásáról, érkezéséről táblázatos formában. A weboldal **HTML** és **CSS** segítségével készült.

Az oldal fiktív információkat tartalmaz. 

### 📌 Funkciók
- 🚊 induló és érkező információi táblázatban
- 🕒 állomás, indulási, érkezési idők megjelenítése
- ✍ a kor szellemének megfelelő design, felhasználóbarát elrendezéssel

### 🚀 Az oldal használata
Pofon egyszerű! 
1. nyisd meg a kedvenc böngésződet! 
2. töltsd be a [MÁV utastájékoztató](https://david-mezei.github.io/2025_01_30_MAV_indulo_jaratok/)
És a rendszer már is betölti az aktuális adatokat.

### 💻 Alap HTML struktúra
```html
<table>
        <thead>
            <tr>
                <th colspan="2" id="ora">8:43:03</th>
                <th colspan="2">MÁV induló járatok</th>
                <th>Arrivals</th>
                <th><img src="mav.png" alt="MÁV logo" width="45px"></th>
            </tr>
            <tr>
                <th>Tervezett érkezés</th>
                <th>Érkezés</th>
                <th>Vonat</th>
                <th>Honnan</th>
                <th>Hova</th>
                <th>Vágány</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>8:30</td>
                <td id="keses">8:42</td>
                <td><img src="ic.png" alt="IC" width="30px"></td>
                <td>Szeged</td>
                <td>Szatymaz - Kistelek</td>
                <td>5</td>
                
            </tr>
            <tr class="paratlan-sor">
                <td>9:22</td>
                <td></td>
                <td><img src="sz.png" width="30px"></td>
                <td>Szentes</td>
                <td>Csongrád</td>
                <td>2</td>
            </tr>
            <tr>
```

### 🎨 CSS stílusok
```css
table, tr, th, td {
    border: 1px solid black;
    border-collapse: collapse;
}

table {
    width: 65%; 
    background-color: #2ab44f; /* háttérszín */
    color: white; /* betűszín */
    font-family: Arial, Helvetica, sans-serif; /* betűtípus */
    
}

th {
    background-color: #237539;
}

#keses {
    background-color: #ff0022;
}

table, tr, th, td {
    border: 1px solid black;
    border-collapse: collapse;
}

table {
    width: 65%; 
    background-color: #2ab44f; /* háttérszín */
    color: white; /* betűszín */
    font-family: Arial, Helvetica, sans-serif; /* betűtípus */
    
}

th {
    background-color: #237539;
}

#keses {
    background-color: #ff0022;
}
```

### 🔥 További, extra funkciók

- real time idő kiírása JS segítségével (Credit: [Varga Ati](https://github.com/VargaAti), és az internet)
- névnapok kiírása JS segítségével (Credit: [github/nevadavid](https://github.com/nevadavid/nevnap))

### 📸 Screenshot a weboldalról

![Screenshot](https://github.com/david-mezei/2025_01_30_MAV_indulo_jaratok/blob/main/images/screenshot.png)

