알기쉬운 챗GPT 생활 데이터 분석
===============================

이 프로젝트는 (주)컴퓨매스에이아이의 첫 번째 책 "알기쉬운 챗GPT 생활 데이터 분석"의 연습 데이터의 링크 및 예제 코드가 포함되어 있습니다.

<a href="https://ebook-product.kyobobook.co.kr/dig/epd/ebook/E000007550831" target="_blank"><img src="images/book_cover.png"></a>

**⚠️⚠️ 다운로드 링크는 해당 사이트의 상황에 따라 유효하지 않을 수 있습니다. ⚠️⚠️**

## 1부. 생활 데이터 분석

#### [[ 예제 데이터 목록 및 다운로드 안내 ]]

##### Kaggle Datasets

이 책에서는 [Kaggle](www.kaggle.com)에서 공개하는 데이터세트 중 다음을 활용합니다. Kaggle에 로그인한 뒤, 각 링크의 `Download`버튼을 클릭하여 데이터를 내려받아서 활용할 수 있습니다.

- [airline_review_1.xlsx](https://www.kaggle.com/datasets/juhibhojani/airline-reviews)
- [cafe.xlsx](https://www.kaggle.com/datasets/mahirahmzh/starbucks-customer-retention-malaysia-survey)
- [churn_test.xlsx, churn_train.xlsx](https://www.kaggle.com/datasets/radheshyamkollipara/bank-customer-churn)
- [marketing_campaign.xlsx](https://www.kaggle.com/datasets/rodsaldanha/arketing-campaign)
- [OnlineRetail_data.xlsx](https://www.kaggle.com/datasets/tunguz/online-retail)
- [onlinedelivery.xlsx](https://www.kaggle.com/datasets/benroshan/online-food-delivery-preferencesbangalore-region)
- [titanic.xlsx](https://www.kaggle.com/datasets/brendan45774/test-file)
- [used_car.xlsx](https://www.kaggle.com/datasets/sujay1844/used-car-prices)

상황에 따라 파일 확장자는 `xlsx` 또는 `csv` 둘 중 하나만 제공하지만, 둘 다 책에서 소개하는 방법으로 예제에서 활용할 수 있습니다.

##### 국토교통부 실거래가 공개 시스템

이 책에서 활용한 아파트 매매/전세 실거래가는 [국토교통부 실거래가 공개 시스템](https://rt.molit.go.kr/pt/xls/xls.do?mobileAt=)링크로 진입(조건별 자료제공)하고, 조건을 선택후 "EXCEL 다운" 또는 "CSV 다운"으로 데이터를 내려받을 수 있습니다. 데이터 검색 조건은 예제의 파일이름을 참고 합니다.

```
- seoul_apt_price.xlsx
- filtered_jeonse_data.xlsx
- 아파트(매매)_실거래가.xlsx
- 아파트(매매)_실거래가_2024_1월.xlsx
- 아파트(매매)_실거래가_2024_2월.xlsx
- 아파트(매매)_실거래가_2024_3월.xlsx
- 아파트(전월세)_실거래가.xlsx
```

##### Opinet

한국석유공사 [오피넷](https://www.opinet.co.kr/user/main/mainView.do)에서 제공하는 [국내 유가 통계](https://www.opinet.co.kr/user/opdown/opDownload.do)자료 조회 링크에서 조걸별로 검색하여 내려받을 수 있습니다. 데이터 검색 조건은 예제의 파일이름을 참고 합니다.

```
- station(강남구).xlsx
```

## 2부. 챗GPT 기술의 이해와 응용

### 3장. Assistants API

#### [[ OpenAI Platform 에서 Thread 메뉴가 보이지 않으면?]]

- 보안상의 이유로 프로젝트에 생성되어있는 Thread 메뉴 접근 권한을 설정할 수 있도록 되어 있습니다.

- OpenAI 계정의 `Settings > Organization > General > Features and capabilities` 메뉴에서 Thread 항목을 모두에게서 감추거나, 소속 단체(Organization) 소유자들에게 보이도록 하거나, 모든 프로젝트 접근자들에게 보여주도록 설정할 수 있습니다.

#### [[ 예제 소스코드 안내 ]]

- 예제 소스코드
    - [Assistants API examples](assistants_api/index.ipynb)

- Colab에서 연습하기

    <a href="https://colab.research.google.com/github/cmai03/book-EasyChatGPTDataAnalysis/blob/main/assistants_api/index.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a> 
   
    ⚠️ _Colab은 임시 환경을 제공하므로 일정 시간이 지나면, 모든 작업은 삭제됩니다. 중요한 데이터는 반드시 다운로드하세요._

#### [[ 예제 데이터 목록 및 다운로드 안내 ]]

예제를 위한 데이터를 다운로드할 수 있는 사이트입니다.

##### 전자공시시스템(https://dart.fss.or.kr/)

아래 다운로드 링크를 클릭하여 파일을 현재 폴더에 저장하고 예제에서 활용합니다.

- ["[삼성전자]사업보고서(2024.03.12).pdf"](https://dart.fss.or.kr/pdf/download/pdf.do?rcp_no=20240312000736&dcm_no=9702846)
- ["[LG전자]사업보고서(2024.03.18).pdf"](https://dart.fss.or.kr/pdf/download/pdf.do?rcp_no=20240318000755&dcm_no=9726985)
- ["[현대자동차]사업보고서(2024.03.13).pdf"](https://dart.fss.or.kr/pdf/download/pdf.do?rcp_no=20240313001451&dcm_no=9709913)

##### U.S. Securities And Exchange Commission(https://www.sec.gov/)

아래 링크의 사이트를 PDF로 인쇄하여 파일이름을 맞추고 현재 폴더에 저장하고 예제에서 활용합니다.

- [amd-10-k-2023.pdf](https://www.sec.gov/Archives/edgar/data/2488/000000248824000012/amd-20231230.htm)
- [apple-10-K-2023.pdf](https://www.sec.gov/Archives/edgar/data/320193/000032019323000106/aapl-20230930.htm)
- [google-10-k-2023.pdf](https://www.sec.gov/Archives/edgar/data/1652044/000165204424000022/goog-20231231.htm)
- [nvidia-10-K-2023.pdf](https://www.sec.gov/Archives/edgar/data/1045810/000104581024000029/nvda-20240128.htm)

##### 국토교통부 실거래가 공개 시스템

이 책에서 활용한 아파트 매매/전세 실거래가는 [국토교통부 실거래가 공개 시스템](https://rt.molit.go.kr/pt/xls/xls.do?mobileAt=)링크로 진입(조건별 자료제공)하고, 조건을 선택후 "EXCEL 다운" 또는 "CSV 다운"으로 데이터를 내려받을 수 있습니다. 데이터 검색 조건은 예제의 파일이름을 참고 합니다.

```
- 아파트(전월세)_실거래가_2024년1월
```