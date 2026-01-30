# Analog BPSK Modulation Simulation with Proteus 📡

This project is a simulation of **BPSK (Binary Phase Shift Keying)** modulation, a fundamental technique in satellite and digital communication systems, implemented using analog components in the Proteus environment.

## 🎯 Project Goal
To observe how a digital data signal (message) modulates an analog carrier signal by shifting its phase and to analyze the working principle of the circuit.

## 📸 Screenshots and Analysis

### 1. Simulation Results (Oscilloscope)
![BPSK Oscilloscope Output](Ekran%20görüntüsü%202026-01-29%20213106.png)
* **Yellow Signal (Message):** Digital data input (Square wave).
* **Blue Signal (Carrier):** High-frequency sine wave.
* **Pink Signal (Modulated Output):** Notice clearly that the phase shifts by **180°** whenever the message signal transitions from logic '1' to '0'.

### 2. Circuit Schematic
![BPSK Circuit Schematic](Ekran%20görüntüsü%202026-01-29%20213128.png)
The circuit uses analog switches to route the carrier signal either directly or through an inverting amplifier (Op-Amp) to the output, depending on the state of the message signal.

## 🛠️ Components Used
* **LM741:** Used as an inverting amplifier (Op-Amp).
* **CD4016:** Analog switch for signal routing.
* **7404 (NOT Gate):** Inverter for the switching logic.

## 🚀 How to Run?
1.  Download this repository.
2.  Open the `.pdsprj` file with **Proteus 8** or newer.
3.  Run the simulation and observe the waveforms on the oscilloscope.

  ---
 # Proteus ile Analog BPSK Modülasyon Simülasyonu 📡

Bu proje, uydu ve dijital haberleşme sistemlerinde temel bir teknik olan **BPSK (Binary Phase Shift Keying)** modülasyonunun analog bileşenler kullanılarak Proteus ortamında gerçekleştirilmiş bir simülasyonudur.

## 🎯 Projenin Amacı
Dijital bir veri sinyalinin (mesaj), analog bir taşıyıcı sinyalin fazını değiştirerek nasıl modüle edildiğini gözlemlemek ve devrenin çalışma prensibini analiz etmektir.

## 📸 Ekran Görüntüleri ve Analiz

### 1. Simülasyon Sonuçları (Osiloskop)
![BPSK Osiloskop Çıktısı](Ekran%20görüntüsü%202026-01-29%20213106.png)
* **Sarı Sinyal (Mesaj):** Dijital veri girişi (Kare dalga).
* **Mavi Sinyal (Taşıyıcı):** Yüksek frekanslı sinüs dalgası.
* **Pembe Sinyal (Modüleli Çıkış):** Mesaj sinyali lojik '1'den '0'a geçtiğinde fazın **180° değiştiği** net bir şekilde görülmektedir.

### 2. Devre Şeması
![BPSK Devre Şeması](Ekran%20görüntüsü%202026-01-29%20213128.png)
Devre, mesaj sinyalinin durumuna göre taşıyıcı sinyali ya doğrudan ya da bir evirici yükselteç (Op-Amp) üzerinden çıkışa yönlendiren analog anahtarlar kullanır.

## 🛠️ Kullanılan Bileşenler
* **LM741:** Evirici yükselteç (Op-Amp).
* **CD4016:** Sinyal yolunu seçen analog anahtar.
* **7404 (NOT Kapısı):** Anahtarlama mantığını terslemek için.

## 🚀 Nasıl Çalıştırılır?
1.  Bu depoyu indirin (Code -> Download ZIP).
2.  `.pdsprj` uzantılı dosyayı **Proteus 8** veya daha yeni bir sürümle açın.
3.  Simülasyonu başlatarak osiloskop çıktılarını inceleyin.
