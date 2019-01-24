Za potrebe ovog projekta odlucio sam testirati sluzbenu web stranicu NBA-a. Testove sam proveo u razvojnom ukruženju Intelliy IDEA korsiteci
JAVA programski jezik i Selenium WebDriver.

Sam kod se sastoji od 8 metoda koje predstavljaju testne slucajeve, metode kojom se "pobuduje" Chrome i main-a u kojom se poziva metoda 
invokeBrowser. Unutar metoda invokeBrowser poziva se jedna od ovih 8 metoda: getTest, searchTest, basketTest, loginTest, registrationTest,
navigateTest, scrollTest, hideShowScoresTest. Mislim da imena metoda dosta govore o tome što koja metoda radi tako da necu detaljno objašnjavati
svaku metodu. Ovisno o testu koji se želi provesti, odkomentira se željena metoda unutar invokeBrowser (ostale su zakomentirane) te se pokrene
program.

NAPOMEA: kao što sam komentirao u kodu, registracija se satsoji od 3 stepa, medutim iz nekog glupog razloga kada se na prvom stepu stisne 
Agree and Continue pocinje se loadati u beskonacnost i ne želi preci na step2. Probao sam sa 3 accounta i uvijek je rezultat isti. Registracija se provede
ali nikad ne ode na step2. Sada imam 3 napravljana racuna na stranici, a ne mogu se obrisati hahahha.

