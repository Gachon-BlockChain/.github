# 🎁 블록은역시레고 (Gachon-BlockChain)

안녕하세요! 저희는 기프티콘 중고 거래의 신뢰 문제를 해결하고자 모인 팀 '블록은역시레고'입니다. 저희는 기프티콘 중고 거래 NFT 마켓플레이스를 개발했습니다.

---

## 🧐 프로젝트 소개: Gifticon NFT

기존의 기프티콘 중고 거래는 다음과 같은 고질적인 문제점들을 가지고 있습니다.

1.  **사기 거래 위험:** 판매자가 이미 사용한 기프티콘(허위 매물)을 올리더라도 플랫폼이 이를 판별하기 어렵습니다. 
2.  **N차 거래의 리스크:** 하나의 기프티콘이 여러 사람에게 재판매될 경우, 모든 중간 판매자가 원본 바코드를 알게 됩니다. 이로 인해 구매 시점에서는 사용 가능했더라도, 중간 판매자 중 누군가가 악의적으로 사용하면 추적이 불가능합니다.

## ✨ 저희의 해결책

저희는 **NFT 기술**과 **암호화**를 통해 이 문제를 해결합니다.

* **NFT 발행 (Minting):** 판매자가 기프티콘을 등록하면, 원본 바코드 이미지는 **암호화**되어 pinata 클라우드에 안전하게 보관됩니다. 그리고 해당 기프티콘은 **NFT**로 발행됩니다. 
* **안전한 거래:** 구매자들은 원본 바코드가 아닌, 이 **NFT**를 거래합니다.
* **NFT 소각 (Decryption & Burn):** 최종 구매자가 '사용하기' (복호화)를 선택하면, 원본 바코드 사진을 전달받으면서 **NFT는 소각(소멸)됩니다.** 
* **신뢰성 확보:** 이 과정을 통해 오직 최종 구매자만이 원본 바코드에 접근할 수 있으며, 재판매 이력이 투명하게 관리되어 최초 판매자 추적이 가능해집니다.

## 🛠️ 주요 기술 스택

| 분야 | 기술 |
| :--- | :--- |
| **Frontend** | Next.js, MetaMask |
| **Blockchain** | Solidity (Smart Contract), Polygon (Amoy) |
| **Storage/Infra** | Pinata |
| **Encryption** | Threshold Access Control (TACO)|

## 📂 Repositories

* **[GifticonNFT-FE](https://github.com/Gachon-BlockChain/GifticonNFT-FE):** 프론트엔드 (React, Next.js)
* **[GifticonNFT-SC](https://github.com/Gachon-BlockChain/GifticonNFT-SC):** 스마트 컨트랙트 (Solidity)

## 👨‍💻 팀원 소개

| 이름 | 담당 |
| :--- | :--- |
| **윤성문** | 스마트컨트랙트 개발/배포, 인프라, Front ABI연동, 발표 |
| **황규한** | PPT, 발표 |
| **이수훈** | Front UI 개발 |
| **남원식** | Front UI 개발 |