# Arsip-tugas-SMA
Lampu lalu lintas
// inisialisasi pin LED
const int ledMerah = 13;
const int ledKuning = 12;
const int ledHijau = 11;

void setup() {
  // Mengatur pin LED sebagai OUTPUT
  pinMode(ledMerah, OUTPUT);
  pinMode(ledKuning, OUTPUT);
  pinMode(ledHijau, OUTPUT);
}

void loop() {
  digitalWrite(ledMerah, HIGH);// Menyalakan lampu merah
  delay(5000); // Lampu merah menyala selama 5 detik
  digitalWrite(ledMerah, LOW);// Mematikan lampu merah
  // Lampu merah mati 

  digitalWrite(ledKuning, HIGH);
  delay (2000);
  digitalWrite(ledKuning, LOW);
  
  digitalWrite(ledHijau, HIGH);
  delay (5000);
  digitalWrite(ledHijau, LOW);
}
