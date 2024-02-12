# **AI Hematologic Diagnosis: White Blood Cell Classification with CNN Model🩸**
*Ramdhina Finita - 02/02/2023*

Publised at Medium: 
- Klasifikasi Gambar Menggunakan Deeplearning Untuk Kasus Sel Darah Putih 🩸 [Part 1](https://medium.com/@ramdhinafinita/klasifikasi-gambar-menggunakan-deeplearning-untuk-kasus-sel-darah-putih-7e1c4a72fa3d)
- Klasifikasi Gambar Menggunakan Deeplearning Untuk Kasus Sel Darah Putih 🩸 [Part 2](https://medium.com/@ramdhinafinita/klasifikasi-gambar-menggunakan-deeplearning-untuk-kasus-sel-darah-putih-part-2-1bfa01fce8ef)
- Klasifikasi Gambar Menggunakan Deeplearning Untuk Kasus Sel Darah Putih 🩸 [Part 3](https://medium.com/@ramdhinafinita/klasifikasi-gambar-menggunakan-deeplearning-untuk-kasus-sel-darah-putih-part-3-ed75936f29e1)


## **Latar Belakang dan Persiapan Data**

Sel darah putih memainkan peran penting dalam bidang diagnosis penyakit terkait darah utama. Tubuh kita terutama mengandung tiga jenis sel darah, yang meliputi sel darah merah, sel darah putih (WBC), dan trombosit. Sel darah putih juga disebut sel imun karena mereka adalah sel dari sistem kekebalan tubuh. Identifikasi penyakit yang berhubungan dengan darah terutama didasarkan pada ciri-ciri atau sifat-sifat inti sel darah putih. Jadi klasifikasi sel darah putih yang andal menjadi penting dan semakin dituntut. Data yang tidak mencukupi merupakan salah satu keterbatasan dalam metode yang sudah ada. Serta elemen latar belakang yang tidak diinginkan dalam kumpulan data dapat mengurangi kinerja dari klasifikasi. Sehingga untuk mengklasifikasikan citra sel darah, metode yang disempurnakan dengan menggunakan pendekatan jaringan saraf convolutional diusulkan. Database WBC digunakan untuk klasifikasi sel darah putih. 

Dengan menggunakan machine learning dengan penggunaan model CNN transfer learning dan juga menggunakan beberapa hypyerparameter tuning, diharapkan model klasifikasi sel darah dengan akurasi terbaik dapat digunakan sebagai prediksi klasifikasi secara cepat dan akurat.

**Hemopatologi** (hemo artinya darah, patologi artinya penyakit), adalah ilmu yang mempelajari penyakit melalui sel darah. Struktur sel darah yang tidak normal, tingkat jumlah sel darah, dan lain sebagainya merupakan beberapa faktor yang dapat digunakan untuk mengidentifikasi beberapa penyakit.

Beberapa penyakit, seperti leukemia, demam berdarah, thalassemia dan malaria, telah menandai perubahan jumlah sel darah putih. Hal ini dikarenakan beberapa jenis sel darah putih hanya dapat melawan jenis penyakit tertentu. Perubahan jumlah sel ini dapat digunakan untuk mengidentifikasi penyakit. Dengan begitu, penggunaan CNN dalam mengidentifikasi sel darah putih dapat bermanfaat sehingga proses identifikasi perubahan jumlah sel darah dapat dilakukan dengan cepat dan akurat menggunakan deep learning.

**Contoh Tampilan klasifikasi Sel Darah Putih**\
Dari: [WBC image classification and generative models based on convolutional neural network](http://https://bmcmedimaging.biomedcentral.com/articles/10.1186/s12880-022-00818-1)
![](https://media.springernature.com/full/springer-static/image/art%3A10.1186%2Fs12880-022-00818-1/MediaObjects/12880_2022_818_Fig1_HTML.png?as=webp)

## **Data**
### [Blood Cell](https://github.com/Shenggan/BCCD_Dataset) 🩸

## **Model**
> [VGG19](https://www.tensorflow.org/api_docs/python/tf/keras/applications/vgg19/VGG19) \
> [ResNet50](https://www.tensorflow.org/api_docs/python/tf/keras/applications/resnet50/ResNet50) \
> [MobileNetV2](https://www.tensorflow.org/api_docs/python/tf/keras/applications/mobilenet_v2/MobileNetV2) 

## **REFERENSI**

* WBC-classification. https://bit.ly/2zbz8oA. Accessed: 2019-06-15.
* [Bagido, R. A., Alzahrani, M., &#38; Arif, M. (2021). White Blood Cell Types Classification Using Deep Learning Models. IJCSNS International Journal of Computer Science and Network Security, 21(9), 223–229. https://doi.org/10.22937/IJCSNS.2021.21.9.30
](https://koreascience.kr/article/JAKO202129436703262.pdf)
* [Jung, C., Abuhamad, M., Mohaisen, D., Han, K., & Nyang, D. (2022). WBC image classification and generative models based on convolutional neural network. BMC Medical Imaging, 22(1). https://doi.org/10.1186/s12880-022-00818-1](https://bmcmedimaging.biomedcentral.com/articles/10.1186/s12880-022-00818-1)
* [Quantology, N. (2022). Hersh A. Muhamad/A Deep Learning Method for Detecting Leukemia in Real Images A Deep Learning Method for Detecting Leukemia in Real Images. 20, 2358–2365. https://doi.org/10.14704/nq.2022.20.7.NQ33305](http://https://www.neuroquantology.com/data-cms/articles/20220722063641pmNQ33305.pdf)
* [Vatathanavaro, Supawit & Tungjitnob, Suchat & Pasupa, Kitsuchart. (2018). White Blood Cell Classification: A Comparison between VGG-16 and ResNet-50 Models.](https://site.ieee.org/thailand-cis/files/2018/11/JSCI6-Paper-2.pdf)
* [Yu, W., Chang, J., Yang, C., Zhang, L., Shen, H., Xia, Y., &#38; Sha, J. (2017, October). Automatic classification of leukocytes using deep neural network. 2017 IEEE 12th International Conference on ASIC (ASICON). http://dx.doi.org/10.1109/asicon.2017.8252657](https://www.researchgate.net/publication/322563590_Automatic_classification_of_leukocytes_using_deep_neural_network)
