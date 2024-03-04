# Submission-Synapsis.id
1. How to run the model apps : 

   * Instalasi Library :
     - !pip install gradio
     - !pip install yolov5
     - !pip install onnx
     - !pip install onnxruntime

   * Load The Model :
     Replace path with the path to your model.
     
     ```python
     import onnxruntime as ort
     ort_session = ort.InferenceSession("/path/to/your/model.onnx")


   * Click run all the notebook

2. About Dataset :
   * Relevansi Topik: Mengingat pandemi COVID-19 yang sedang berlangsung, penggunaan PPE (Perlindungan Diri) menjadi 
     sangat penting. Dataset ini berisi gambar PPE yang digunakan dalam konteks COVID-19, membuatnya sangat relevan dan 
     tepat waktu1.
   * Label yang Jelas: Dataset ini telah dikurasi dan dilabeli untuk deteksi objek PPE untuk COVID-191. Ini berarti 
     bahwa data sudah siap untuk digunakan dalam pelatihan model deteksi objek, menghemat waktu dan upaya yang biasanya 
     diperlukan untuk proses anotasi.
   * Varietas Kelas: Dataset ini mencakup berbagai jenis PPE, termasuk sarung tangan, masker, pelindung wajah, 
     coverall, dan kacamata. Varietas ini memberikan model Anda kemampuan untuk mengenali dan membedakan antara 
     berbagai jenis PPE2.
   * Penerapan Praktis: Model yang dilatih pada dataset ini dapat memiliki berbagai aplikasi praktis, termasuk 
     penggunaan di institusi kesehatan dan tempat berkapasitas tinggi seperti mal untuk memastikan kepatuhan PPE2.
   * Kontribusi terhadap Penelitian COVID-19: Dengan menggunakan dataset ini, Anda berkontribusi pada upaya penelitian 
     yang lebih luas untuk melawan COVID-19. Model yang Anda latih dapat digunakan untuk memastikan kepatuhan terhadap 
     protokol keselamatan dan dapat membantu dalam meminimalkan penyebaran virus

  3. Doc Metrics Preview :
     
     <img width="1145" alt="Screen Shot 2024-03-04 at 17 22 42" src="https://github.com/dimasmuly/submission/assets/64884902/dea7eaae-d1c1-4074-828c-bdc8b9692a4b">
     <img width="1151" alt="Screen Shot 2024-03-04 at 17 22 24" src="https://github.com/dimasmuly/submission/assets/64884902/17b80f02-e467-480d-961a-5771b25895eb">
     <img width="1146" alt="Screen Shot 2024-03-04 at 17 22 03" src="https://github.com/dimasmuly/submission/assets/64884902/f44d3174-d6b2-4568-aebb-3b0d89121129">
     <img width="1151" alt="Screen Shot 2024-03-04 at 17 21 31" src="https://github.com/dimasmuly/submission/assets/64884902/6e236252-44a4-48b1-a40b-07c9aab2ed3f">
     <img width="1148" alt="Screen Shot 2024-03-04 at 17 21 05" src="https://github.com/dimasmuly/submission/assets/64884902/5df66805-4540-43d5-9140-f0e347683e02">


     

