# 'Who Am I' - Capture the Flag

As part of the ICSD 2024 conference, we had the privilege of hosting the Capture the Flag (CTF) competition, Who Am I.

A total of 20 teams, each consisting of 2-3 participants, competed for a prize pool of 9,000 AZN, with 5,000 AZN awarded to the first-place team, 3,000 AZN to the second, and 1,000 AZN to the third. The competition took place on September 20th, running from 08:30 to 14:15, lasting nearly six hours.

Boşver emerged as the winner, scoring 1,080 out of a possible 2,100 points. BHOSploit claimed second place with 1,030 points, and Kabiner secured third place with 800 points.

In this repository, we will share all the challenges used during the competition, along with what we consider to be the correct solutions. Additionally, we will provide statistics on the competitors, teams, and individual questions.

# General Information
## Challanges
A total of 12 challenges were presented to the competitors, each consisting of one or more questions, amounting to 31 questions in total.

Challenges covered various aspects of cybersecurity such as Cryptograhy, OSINT, Steganography, Log Analysis, Disk Forensics, Penetration Testing and Privilege Escalation. Each challenge was assigned a total score, which was distributed across the questions based on their difficulty level. 


| Challenge Name               | Difficulty | Challenge Score | Question Count | Score for each Question           | Covers                                    |
|------------------------------|------------|-----------------|----------------|-----------------------------------|-------------------------------------------|
| **C1: Death Token**               | Easy       | 100             | 1              | 100                               | Cryptography                              |
| **C1: Decode the Escape**         | Easy       | 100             | 1              | 100                               | Cryptography                              |
| **C3: ANAIS_WATT3RSON**           | Easy       | 100             | 1              | 100                               | OSINT                                     |
| **C4: #exec cmd= “whoami”**       | Easy       | 125             | 4              | 25, 30, 30, 40                    | Steganography, OSINT                      |
| **C5: Packet Detective**          | Easy       | 125             | 9              | 10, 10, 10, 10, 10, 15, 15, 20, 25| Forensics, Packet Analysis                |
| **C6: Exorcising Sukuna’s Curse** | Medium     | 130             | 2              | 60, 70                            | Vulnerability Exploitation                |
| **C7: Root Reaper Quest**         | Medium     | 150             | 1              | 150                               | Log Analysis                              |
| **C8: In Quest for Rogue Dragon** | Medium     | 170             | 2              | 100, 70                           | Reverse Engineering                       |
| **C9: End of Rumbling**           | Hard       | 200             | 2              | 100, 100                          | Active Directory Exploitation             |
| **C10: Shadows Possession Jutsu** | Hard       | 250             | 3              | 100, 75, 75                       | Forensics, Disk Analysis                  |
| **C11: Serial Escape**            | Hard       | 250             | 3              | 100, 100, 50                      | Web Exploitation                          |
| **C12: Mr. Windoclin**            | Hard       | 300             | 2              | 150, 150                          | Vulnerability Exploitation, Docker Escape |
| **Total**                     |            | **2000**        | **31**         |                                   |                                           |

## Standings

> [!IMPORTANT]  
> All flag submission attempts (whether correct or incorrect) have been logged and are available in 'ctf_submission_logs.csv' file. 

| N#  | Team Name    | C1  | C2  | C3  | C4            | C5               | C6  | C7  | C8  | C9  | C10       | C11 | C12 | Score | Extra | Total |
| :---: | :---:      | :---: | :---: | :---: | :---:          | :---:             | :---: | :---: | :---: | :---: | :---:     | :---: | :---: | :---: | :---: | :---: |
| 1   | boşver      | 100 | -   | 100 | 125            | 125               | 130 | 150 | -   | -   | -         | 250  | -    | 980   | 100   | 1080  |
| 2   | BHOSsploit  | 100 | 100 | 100 | 125            | 125               | 130 | -   | -   | -   | -         | 100  | 150  | 930   | 100   | 1030  |
| 3   | Kaniber     | 100 | -   | 100 | 125            | 125               | -   | 150 | -   | -   | -         | 100  | -    | 700   | 100   | 800   |
| 4   | SUDOERS     | 100 | -   | -   | 85(+++-)       | 100(+-+++-+++)    | -   | 150 | 100(+-) | - | 100(+--) | -    | -    | 635   | 100   | 735   |
| 5   | 405 Found   | -   | -   | 100 | 125            | 125               | 130 | 150 | -   | -   | -         | -    | -    | 630   | 100   | 730   |
| 6   | Felina      | 100 | 100 | -   | 125            | 125               | 130 | -   | -   | -   | -         | -    | -    | 580   | 100   | 680   |
| 7   | R3d3f3nd    | 100 | -   | 100 | 125            | 110(+++++-+++)    | 130 | -   | -   | -   | -         | -    | -    | 565   | 100   | 665   |
| 8   | Zero Zero   | -   | -   | -   | 125            | 110(+++++-+++)    | 130 | 150 | -   | -   | -         | -    | -    | 515   | 100   | 615   |
| 9   | ASCCA       | -   | -   | 100 | 125            | 110(+++++-+++)    | -   | 150 | -   | -   | -         | -    | -    | 485   | 100   | 585   |
| 10  | Cerberus    | -   | -   | 100 | 125            | 100(+-+++-+++)    | 130 | -   | -   | -   | -         | -    | -    | 455   | 100   | 555   |
| 11  | CyberCell   | 100 | -   | -   | 85(+++-)       | 110(+++++-+++)    | -   | 150 | -   | -   | -         | -    | -    | 445   | 100   | 545   |
| 12  | FR13NDS     | 100 | -   | -   | 85(+++-)       | 115(+-+++++++)    | 130 | -   | -   | -   | -         | -    | -    | 430   | 100   | 530   |
| 13  | AzInfosec   | -   | -   | -   | 125            | 115(+-+++++++)    | 130 | -   | -   | -   | -         | -    | -    | 370   | 100   | 470   |
| 14  | Iron First  | -   | -   | -   | 85(+++-)       | 110(+++++-+++)    | -   | 150 | -   | -   | -         | -    | -    | 345   | 100   | 445   |
| 15  | Cyberstars  | 100 | -   | -   | 85(+++-)       | 110(+++++-+++)    | -   | -   | -   | -   | -         | -    | -    | 295   | 100   | 395   |
| 16  | 127.0.0.Biz | -   | -   | -   | 55(+-+-)       | 115(+-+++++++)    | -   | -   | -   | -   | -         | -    | -    | 170   | 100   | 270   |
| 17  | Leet Duo    | -   | -   | -   | 85(+++-)       | 20(+-+------)     | -   | -   | -   | -   | -         | -    | -    | 105   | 100   | 205   |
| 18  | Fourier     | -   | -   | -   | 85(+++-)       | 10(+--------)     | -   | -   | -   | -   | -         | -    | -    | 95    | 0     | 95    |
| 19  | CyberSpace  | -   | -   | -   | 25(+---)       | 10(+--------)     | -   | -   | -   | -   | -         | -    | -    | 35    | 0     | 35    |
| 20  | Overclock   | -   | -   | - | - | - | - | - | - | - | - | - | -| 0 | 0 | 0 |

> [!NOTE]  
> Extra 100 points are awarded for filling a form about PROCYBERLAB platform.

## Some pictures from the competition

