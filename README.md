# Qiskit Fall Fest 2026 · Sabancı Üniversitesi
## Kuantum Programlamaya Giriş Atölyesi

Bu depo, Qiskit ile kuantum programlamaya giriş atölyesinin not defterlerini içerir. Kuantum programlama ya da Qiskit bilgisi gerekmez; temel Python ve lise matematiği yeterlidir.

## Program

| Bölüm | Konu | |
|---|---|---|
| — | Açılış ve Colab kurulumu | |
| 1 | Bitten kubite: klasik ve olasılıksal bit, kubit, ölçüm, X, Z, H ve RY kapıları, girişim, birim çember | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/akifkoc/sabanci-qiskitfallfest26/blob/main/1-kubit.ipynb) |
| — | Ara | |
| 2 | Birden fazla kubit: tansör çarpımı, Qiskit'te kubit sırası, CNOT | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/akifkoc/sabanci-qiskitfallfest26/blob/main/2-cok_kubitli_sistemler.ipynb) |
| 3 | Dolaşıklık, Bell durumları ve yoğun kodlama | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/akifkoc/sabanci-qiskitfallfest26/blob/main/3-dolasiklik_ve_yogun_kodlama.ipynb) |
| — | Sorular ve kapanış | |
| Ek | Birim çember, RY kapısı ve kuantum telenakil (zaman kalırsa) | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/akifkoc/sabanci-qiskitfallfest26/blob/main/4-ek_birim_cember_ve_telenakil.ipynb) |

## Not defterlerini çalıştırma

### Google Colab (önerilen)

Yukarıdaki "Open in Colab" düğmelerine tıklayın. Google hesabınızla giriş yapmanız yeterli; bilgisayarınıza bir şey kurmanız gerekmez.

Her not defterinin ilk kod hücresi Qiskit'i kurar (yaklaşık 1 dakika). Colab her not defterini ayrı bir oturumda açtığı için bu hücreyi her not defterinde bir kez çalıştırın.

### Kendi bilgisayarınızda

Python 3.11 veya daha yeni bir sürüm gerekir.

```bash
pip install -r requirements.txt
jupyter lab
```

Qiskit'i yerel olarak kurmak uzun sürebileceği için atölye sırasında Colab'ı öneriyoruz.

## Daha fazlası

- **QWorld QBook101:** [qworld.net/qbook101](https://qworld.net/qbook101/). Bu atölyenin konularını çok daha ayrıntılı işleyen, alıştırmalarla dolu ücretsiz bir kitap.
- **IBM Quantum Learning:** [quantum.cloud.ibm.com/learning](https://quantum.cloud.ibm.com/learning/en). Özellikle *Basics of Quantum Information* ve *Use a quantum computer today* kursları.
- **Qiskit belgelendirmesi:** [quantum.cloud.ibm.com/docs](https://quantum.cloud.ibm.com/docs)

## Kullanılan sürümler

Qiskit 2.6.0 ve Qiskit Aer 0.18.0.

## Kaynaklar ve lisans

- Not defterleri, Özlem Salehi Köken'in hazırladığı ve Sabancı Üniversitesi'ndeki önceki Qiskit Fall Fest atölyesinde kullanılan materyali temel alır.
- Bazı bölümler QWorld'ün [QBook101](https://gitlab.com/qworld/qeducation/qbook101) kitabından yararlanır: kuantum yazı-tura deneyi ve görselleri, birim çember gösterimi ve kuantum telenakil anlatımı. QBook101'in metin ve görselleri [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/), kodları [Apache 2.0](http://www.apache.org/licenses/LICENSE-2.0) lisansı altındadır. Kuantum yazı-tura görselleri doğrudan QBook101 deposundan gösterilmektedir.
- **QTürkiye (Kuantum Türkiye):** [qturkiye.org/events](https://qturkiye.org/events/). QWorld'ün Türkiye grubu; Türkçe atölyeler ve hackathonlar düzenliyor. Türkçe haber ve içerikler için: [kuantumturkiye.org](https://kuantumturkiye.org).
- Bu depo [Apache 2.0](LICENSE) lisansı altındadır.
