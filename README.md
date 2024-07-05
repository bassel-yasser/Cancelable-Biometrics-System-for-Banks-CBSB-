# Cancelable-Biometrics-System-for-Banks-CBSB

## Introduction

With the increasing number of cyberattacks, traditional security measures such as Personal Identification Numbers (PINs), tokens, and passwords are no longer sufficient for identity protection. Over the past decade, biometric systems have gained popularity as effective security mechanisms for user authentication. However, it is essential to protect user data stored in biometric systems from hackers. This project addresses the safety of biometric data using the technique of 'Cancelable Biometrics.'

A cancelable biometric system for multi-instance biometrics has been designed using deep learning. The proposed solution employs a deep learning architecture based on Convolutional Neural Network (CNN) and Multi-Layer Perceptron (MLP) to create a novel, accurate, and secure cancelable biometric solution. This system has been implemented on a cloud platform to provide a ubiquitous cancelable biometric authentication service.

Cancelable Biometrics (CB), also known as Revocable Biometrics (RB), involve techniques that secure biometric templates through systematic and intentional distortion of biometric features. This significant distortion prevents the original biometric template from being easily deciphered by third parties or attackers. If a cancelable template is stolen or lost, it can be replaced with a new version, ensuring continuous protection.

The verification process uses cancelable templates instead of original biometric templates. In this project, the biometric template is created using a novel feature extraction method with a CNN. Extracted biometric features are then transformed into a cancelable template through the technique of Random Projection, creating a distorted representation that is not invertible to its original form. This protects the user's biometrics from template inversion attacks. The cancelable template is stored in the database for user authentication, while the original biometric is discarded.

Multi-instance biometrics of iris and finger veins are utilized in this project. Multi-instance refers to using different source samples of the same biometric, such as right and left iris samples or index and middle finger veins. Employing multi-instance biometrics increases the security, reliability, and confidence of authentication. For biometric matching, a novel MLP architecture is proposed to achieve high verification accuracy. To provide an efficient, fast, and low-cost solution for biometric authentication, the overall model is implemented on a cloud platform, enabling it to be used as a biometric service accessible through web APIs like XML-RPC and JSON-RPC. 

Results demonstrate that the proposed cancelable biometric system is highly accurate and secure. The cloud implementation leverages parallel processing, making the solution computationally faster than standalone systems while maintaining accuracy and reducing costs.

## Biometric Technology Fundamentals

Biometric authentication has gained immense popularity over traditional methods like PINs, passwords, and tokens. In today's information age, security is crucial for data access and storage, prompting organizations to seek more reliable authentication methods. Traditional methods often underperform due to issues such as being easily lost, forgotten, stolen, or deducible. According to a 2019 report by Verizon, passwords account for 81% of data breaches. To address these issues, many organizations are adopting biometric authentication. It is widely used in consumer devices like mobile phones, by law enforcement for criminal identification, and in nationwide identity schemes such as India's Aadhar, which boasts the largest biometric enrollment of 1.2 billion people.

for more information : https://ieeexplore.ieee.org/document/10479619
