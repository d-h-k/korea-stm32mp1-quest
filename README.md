![coverstory](https://github.com/marcusjang78/korea-stm32mp1-quest/blob/master/images/coverstory1.png?raw=true)


## STM32MP1 QUEST란?

STM32MP1 Microprocessor와 Ecosystem에 대해 단계별로 학습하여, 각 단계에 맞춰 설정된 목표를 실습하는 과정입니다.

------------


### Quest 일정

| Title | Date | Week | Note
| :------------: | :------------: |:------------: |:------------: |
| Orientation | 2020.01.09 | week.2 | |
| Quest-1 | 2020.01.13 ~ 17 | week.3 | |
| Quest-2 | 2020.01.20 ~ 31 | week.4/5 | 구정 연휴로 인해 2주간 진행
| Quest-3 | 2020.02.03 ~ 07 | week.6 | ||
> 이 후 일정에 대해서는 지속적으로 업데이트 예정.

------------


### Quest 보드
- MP1 디스커버리 보드: [STM32MP157C-DK2](https://www.st.com/en/evaluation-tools/stm32mp157c-dk2.html)
![DK2](https://github.com/marcusjang78/korea-stm32mp1-quest/blob/master/images/mp1-disco.jpg?raw=true | width=480)
- 스토리지 용 microSD 카드 (DK2 보드에 기본 포함되어 있음)
- 1 x USB micro-B 타입 케이블 (for ST-LINK, SWD)
- 2 x USB type-C 케이블 (1 for power supply, 1 for terminal/USB-DFU)
> USB hub를 통한 전원 공급의 경우 전류 요구치에 미달할 수 있으므로 가급적 USB charger 사용 권장 (5V/3A 권장)
- 1 x 이더넷 케이블

------------


### Host PC
- 권장 PC 사양
 - CPU
  -- Native 기준: 인텔 2세대 (Sandy Bridge-M) i5 이상
  -- Virutal machine 기준: 인텔 3세대 (Ivy Bridge-M) i5 이상
 - RAM: 8G 이상
 - Storage: 500G 이상 (SSD 추천)
- 운영체제(OS)
 - [Ubuntu 18.04 LTS](https://ubuntu.com/#download)
- 최소 요구 환경
 - USB x 2 포트 (terminal/USB-DFU, ST-LINK, SWD)
 - Ethernet LAN 포트 (RJ45)

------------


### 그외 참조

 - [STM32MP1 Wiki](https://wiki.st.com/stm32mpu/index.php/Main_Page)


*This is for MP1 Quest project for Korea distribution engineers.*
