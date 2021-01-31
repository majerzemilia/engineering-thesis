# engineering-thesis
### Engineer's Thesis written at AGH University of Science and Technology  

##### Summary
&nbsp;&nbsp;The aim of the study was creating a system for classifying photographs of the surface of aircraft
structures according to the occurrence of corrosion. The system should consist of a convolutional neural
network trained to effectively identify corrosion on the skin. Interaction with the classifier should be
carried out with web application. Fundamental subject for the created thesis was Machine Learning
(Uczenie Maszynowe). 

&nbsp;&nbsp;The study was created owing to obtaining the DAIS System database containing photographs of
fragments of the aircrafts’ structures by the Department of Computer Science of AGH University of
Science and Technology. The thesis was created in the framework of the real project on analyzing
damage to the surface of aircraft structures and deals with a real need of improving the analysis
process.  

&nbsp;&nbsp;The Engineer's Thesis contains documentation of the planning process, including technologies’
comparative analysis and functional and non-functional requirements specification, and also some of the
implementation aspects and the results. The created system was built using Flask (web application),
Tensorflow and Keras (finding neural network) frameworks. During the experiments which led to
choosing the efficient neural network for the system, the state of the art architectures and various
machine learning methods and preprocessing techniques (data standardization and data normalization,
ensemble learning, classification of the features returned by convolutional layers of neural networks by
SVM, thresholding) were tested.

&nbsp;&nbsp;The final product utilizes a neural network based on EfficientNetB0 architecture, trained on
standardized data. The network achieved 75% accuracy on the test set, correctly classifying 90% of
photos showing corroded surfaces.
  
##### Streszczenie
&nbsp;&nbsp;Celem pracy było stworzenie systemu do predykcji występowania korozji na zdjęciach poszyć statków
powietrznych. Główną część systemu miała stanowić konwolucyjna sieć neuronowa, wytrenowana do
skutecznego rozpoznawania obecności rdzy na poszyciu. Interakcja z klasyfikatorem miała być
zapewniona poprzez przygotowaną aplikację webową. Przedmiotem bazowym dla powstałej pracy było
Uczenie Maszynowe.  

&nbsp;&nbsp;Praca powstała dzięki uzyskaniu przez Katedrę Informatyki AGH bazy zdjęć z systemu DAIS,
przedstawiających fragmenty poszycia. Powstawała ona w ramach rzeczywistego projektu związanego z
analizą uszkodzeń powierzchni statków powietrznych i dotyczy realnej potrzeby usprawnienia procesu
analizy poszycia.  

&nbsp;&nbsp;W pracy inżynierskiej udokumentowany został proces planowania systemu, obejmujący analizę
technologiczną oraz specyfikację wymagań funkcjonalnych i niefunkcjonalnych, a także wybrane
aspekty jego realizacji oraz wyniki. Powstały system został zbudowany na bazie frameworków Flask
(tworzenie aplikacji webowej) oraz TensorFlow i Keras (przygotowanie sieci neuronowej). Podczas
eksperymentów mających na celu wytrenowanie użytecznej sieci neuronowej dla systemu, testowane
były architektury uważane za state of the art oraz różne metody Uczenia Maszynowego i przygotowania
danych (standaryzacja i normalizacja danych, klasyfikatory zespołowe, klasyfikacja cech uzyskanych
przy pomocy sieci konwolucyjnej przez SVM, modyfikacja progów przynależności obrazu do klasy
pozytywnej).

&nbsp;&nbsp;Końcowy produkt wykorzystuje sieć stworzoną na bazie architektury EfficientNetB0, wytrenowaną na
danych poddanych standaryzacji. Sieć osiągnęła 75% skuteczności na zbiorze testowym, poprawnie
klasyfikując 90% zdjęć zawierających fragmenty poszycia z oznakami korozji.  
