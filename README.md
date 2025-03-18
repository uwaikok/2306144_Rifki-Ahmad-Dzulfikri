# 2306144_Rifki-Ahmad-Dzulfikri
 Greedy Best-First Search (GBFS)

Memilih node berdasarkan heuristik (h(n)) saja (perkiraan jarak ke tujuan).
Cepat, tetapi tidak selalu menemukan jalur terpendek.
Rentan buntu jika heuristik tidak akurat.

 A Search*

Menggunakan g(n) + h(n) (biaya aktual + heuristik).
Lebih optimal, selalu menemukan jalur terpendek.
Lebih lambat dari GBFS karena mempertimbangkan semua kemungkinan jalur.

 Kesimpulan:

Gunakan GBFS jika ingin pencarian cepat.
Gunakan A* jika ingin jalur optimal.
