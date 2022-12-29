# Arduino_7Segmentdisp_leds
LED control with seven segment display and buttons and a system in which the number of LEDs on is displayed on the screen.



// Bu projedeki temel amacımız 7 segment display ve 8 bit kaydırma yazmacını led ve basma butonları ile kombine ederek kullanımını öğrenmektir. Bu projede 4 farklı görevde buton kullandık. bu butonların görevleri sırasıyla soldan anlatmak gerekirse:
1. buton ledler sağ taraftan itibaren yanmaya başlar. ve bu süreç esnasında 7 segment displayde de kaç adet led yanıyor ise o sayı ekrana yazdırılır. 
2. butona basıldığında ise :
ledler sağ ve soldan 2 şer adet yanmaya başlar. ortaya gelindiğinde ise tekrardan sönerek sağa ve sola ilerler. bu tam olarak 1 döngü sayılır. bu döngü bu şekilde devam ettikçe displaydeki sayı da 1 artarak devam eder. 
3. butona basıldığında ise: 
8 segment display 9 dan geriye saymaya başlar. sayaç 0 olduğunda birkaç kez yanıp sönmeye başlar. daha sonra ise ledler sağdan başlayararak ghızlı bir şekilde kayma hareketi yapar.
4. buton ise reset butonudur. sayaç ve ledlerin durumunu sıfırlar. 


// Our main goal in this project is to learn how to use 7 segment display and 8 bit shift register in combination with led and push buttons. In this project, we used buttons in 4 different tasks. To explain the duties of these buttons, respectively, from the left:
1st button leds start to light from the right side. and during this process, how many LEDs are lit on the 7 segment display, that number is printed on the screen.
When the 2nd button is pressed:
LEDs start to light 2 each from the right and left. when it comes to the middle, it goes off again and moves to the right and left. this counts exactly 1 cycle. As this cycle continues in this way, the number on the display continues to increase by 1.
When the 3rd button is pressed:
8 segment display starts counting down from 9. when the counter is 0, it starts flashing several times. then the leds start from the right and make a rapid sliding movement.
The 4th button is the reset button. resets the state of the counter and leds.


// Unser Hauptziel in diesem Projekt ist es zu lernen, wie man 7-Segment-Anzeige und 8-Bit-Schieberegister in Kombination mit LED und Drucktasten verwendet. In diesem Projekt haben wir Schaltflächen in 4 verschiedenen Aufgaben verwendet. Zur Erläuterung der Aufgaben dieser Schaltflächen jeweils von links:
Die LEDs der 1. Taste beginnen von rechts zu leuchten. und während dieses Vorgangs, wie viele LEDs auf der 7-Segment-Anzeige leuchten, wird diese Zahl auf dem Bildschirm gedruckt.
Wenn die 2. Taste gedrückt wird:
LEDs beginnen je 2 von rechts und links zu leuchten. Wenn es in die Mitte kommt, geht es wieder aus und bewegt sich nach rechts und links. dies zählt genau 1 Zyklus. Während dieser Zyklus auf diese Weise fortgesetzt wird, erhöht sich die Zahl auf dem Display weiterhin um 1.
Wenn die 3. Taste gedrückt wird:
Die 8-Segment-Anzeige beginnt mit dem Countdown von 9. Wenn der Zähler 0 ist, beginnt er mehrmals zu blinken. dann beginnen die leds von rechts und machen eine schnelle gleitbewegung.
Die 4. Taste ist die Reset-Taste. setzt den Zustand des Zählers und der LEDs zurück.
