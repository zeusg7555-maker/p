```mermaid
flowchart TB

classDef default fill:#ffffff,stroke:#000000,color:#000000,font-size:14px;

subgraph FR ["Faktor Risiko pada Pelari"]
  FR1[Overuse & repetitive strain]
  FR2[Biomekanik lari buruk]
  FR3[Muscle fatigue]
  FR4[Mobilitas terbatas / riwayat cedera]
end

FR1 --> MT[Mikrotrauma berulang]
FR2 --> MT
FR3 --> MT
FR4 --> MT

MT --> IC[Iskemia & Energy Crisis]

IC --> ME[Disfungsi motor endplate\n(ACh ↑)]
IC --> SP[Sensitisasi perifer & sentral]
IC --> TB[Pembentukan taut band & Trigger Point]

ME --> MPS[Myofascial Pain Syndrome\nGastrocnemius]
SP --> MPS
TB --> MPS

MPS --> GC[Gejala Klinis:\nNyeri, kekakuan, trigger point,\npenurunan power]
MPS --> GP[Gangguan performa lari]

GC --> DN[Dry Needling pada MTrP\n→ memicu LTR]
GP --> DN

DN --> MT2[Mikrotrauma jarum\n& inflamasi lokal]
DN --> LTR2[LTR kuat → stres serabut otot]

MT2 --> PNS[Post-Needling Soreness (PNS)]
LTR2 --> PNS

PNS --> PB[Latihan terganggu\n(performa & kepatuhan ↓)]
PNS --> HD[Pemulihan lebih lama]

PB --> TENS_INST[TENS (Intervensi)]
HD --> TENS_INST

subgraph TM ["Mekanisme TENS"]
  T1[Gate Control:\naktivasi Aβ → blokade nyeri]
  T2[Opioid endogen ↑]
  T3[Sirkulasi lokal ↑ → metabolit dibuang]
  T4[Penurunan sensitisasi nociceptor]
end

TENS_INST --> T1
TENS_INST --> T2
TENS_INST --> T3
TENS_INST --> T4

T1 --> REC[Penurunan PNS]
T2 --> REC
T3 --> REC
T4 --> REC

REC --> BACK[Pelari kembali berlatih optimal]
```
