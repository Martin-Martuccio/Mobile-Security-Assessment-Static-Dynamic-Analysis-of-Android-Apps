# Mobile Security Report

## Introduction

This repository contains a security report on two mobile applications, referred to as **APP1** and **APP2** (names censored for legal reasons). The purpose of the report is purely educational, aiming to demonstrate how to analyze vulnerabilities in Android applications using automated security analysis tools.

[📄 Download the full report (PDF)](Mobile_Security_Censured.pdf)


### Report Content

The report is divided into several sections:

1. **Introduction**
   - Objectives of the analysis
   - Methodology and tools used
2. **APP1 Analysis**
   - Static analysis
   - Dynamic analysis
   - Final considerations
3. **APP2 Analysis**
   - Static analysis
   - Dynamic analysis
   - Final considerations

## Tools Used

The following security tools were used to conduct the analysis:

- **[MobSF (Mobile Security Framework)](https://github.com/MobSF/Mobile-Security-Framework-MobSF)**: A framework for static and dynamic analysis of mobile applications.
- **[APKTool](https://apktool.org/)**: A tool for decompiling and modifying APK files.
- **[Magisk](https://github.com/topjohnwu/Magisk)**: A tool for obtaining root privileges in a safe and reversible manner.
- **[Android Studio (Emulator)](https://developer.android.com/studio)**: A testing environment for Android applications.
- **[Charles Proxy](https://www.charlesproxy.com/)**: A tool for analyzing network traffic.
- **[Drozer](https://github.com/WithSecureLabs/drozer)**: A framework for analyzing vulnerabilities in Android components.

## Methodology

The application analysis was conducted following these steps:

1. **APK Download**
2. **Static Analysis**: Decompiling and verifying the security of the code, configurations, and dependencies.
3. **Dynamic Analysis**: Testing on an emulated device with network traffic monitoring tools and vulnerability verification.
4. **Identification and Contextualization of Vulnerabilities**: Classifying security issues and possible mitigations.

## Disclaimer

This report is created solely for educational and research purposes. No terms of service or legal regulations have been violated. None of the information contained in this repository should be used for illegal or malicious purposes.

## Author

Martin Martuccio - University of Genoa
