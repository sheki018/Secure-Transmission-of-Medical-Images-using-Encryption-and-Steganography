# Secure Transmission of Medical Images using Encryption and Steganography

Patients’ data are stored in an electronic record known as Electronic Health Record (EHR). This EHR should be kept conﬁdential because it contains sensitive patient information. Recent development in communication and information technology provides easy and simple access to any data, but the most significant requirement is the establishment of secure communication. Patient’s information is available in various online repositories due to the insecure network of hospitals and clinics. This is a serious ethical issue that has to be addressed. 

Also, these records are transmitted over multiple networks whether local or wide area networks. These transmissions are governed by Digital Imaging and Communications in Medicine (DICOM) standard, to avoid any altering of the data, capturing and copyright protection. The DICOM ﬁle that contains the patients’ information needs to be kept conﬁdential.

Several techniques are developed for safe communication. Some of them include cryptography and steganography. By leveraging the advantages of both techniques, it is possible to safely transmit medical information and images across hospital networks.
The major contribution of this project is combining several steganography and encryption techniques, for secure transmission of data without leakage and unauthorized access. This is achieved as follows: 
- Firstly, the patient’s data which is present in the DICOM header is encrypted using DNA based Advanced Encryption Standard (AES) algorithm. 
- Secondly, Least Significant Bit (LSB) embedding is performed to hide the patient's information inside the image that is used as a cover object. 
- Thirdly, to keep the stego image size reasonable Discrete Wavelet Transform compression is performed and transmitted to the receiver. 
- Finally, the receiver performs the reverse of the proposed process to extract the secret data. 

 Experiments are conducted to evaluate the performance of proposed combined steganography techniques using various statistical metrics and results indicate that the proposed technique outperforms all existing techniques. 
