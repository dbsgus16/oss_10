## 제목: 농업분야에서 활용되는 ERPNext 조사 및 연구

팀원: 
* 생물산업기계공학과/2023013699/윤현서(dbsgus16)
* 산림과학조경학부/2022113523/홍예준(sangililsang)
* 지구시스템과학부지질학전공/2023003586/손승민(Seungminson04)
* 생물산업기계공학과/2023017765/정혜주(hophopflog)
* 

### 1. 개요
   
   ERPNext는 인도 소프트웨어 회사인 Frappe Technologies Pvt가 개발한 무료 오픈 소스 통합 ERP(Enterprise Resource Planning) 소프트웨어다. ERPNext는 기업 내의 다양한 부서 및 기능을 통합하여 관리하는 데 사용되는 시스템으로, 재고 관리, 회계, 인사, 생산 등 다양한 업무를 효율적으로 관리할 수 있다. Python으로 개발되었으며, 사용자 친화적인 사용자 인터페이스와 다양한 모듈을 제공한다.

### 2. 라이선스
   
   ERPNext 코드는 GNU General Public License(v3)로 라이선스되며 문서는 크리에이티브 커먼즈(CC-BY-SA-3.0)로 라이선스되며, 저작권은 Frappe Technologies Pvt Ltd(Frappe) 및 기고자가 소유한다. 무료로 사용할 수 있으며, 오픈 소스이기 때문에 사용자들은 소스 코드에 접근하여 필요에 따라 수정하거나 개선할 수 있다.

### 3. 주요기능
   
#### 1)Diseases & Fertilizers Management / 이수연


농업 분야의 ERPNext은 최신 기술을 이용하여 농가에서 재배하는 작물의 질을 향상, 농가의 수익을 올리기 위한 관리 기능(tool) 역시 보유하고 있다.
예를 들어, 곤충과 균류 등 ‘해충’은 재배하는 작물을 가해함으로써 작물의 품질과 생산량을 모두 떨어트린다. 이에 ERPNext는 작물에 발생하는 식물병을 효율적으로 관리, 통제하는 데 도움을 주는 기능을 도입하여 감염률을 낮추고, 결과적으로 농가의 수익 하락 방지를 도모한다.
또한 비료를 살포할 때에도 ERPNext를 사용하면 용이하다. 작물 별 비료 종류와 살포할 양, 살포 도구 및 살포 기록을 저장할 수 있다.




기본 설정: 우선 Quality Management 섹션에서 원하는 작물의 시작 템플릿(inception template)을 생성한다. 그리고 색, 영양 함량, 크기 등의 원하는 품질의 기준을 정하고, 그 목표값과 최솟값~최댓값 구간을 입력한다. 여기에 ERPNext 주도의 표준 품질 보증 점검을 거쳐, 농작물의 품질이 적절한지 파악한다. 품질 기준을 벗어난 경우, 농가는 ERPNext의 부적합 관리 기능을 이용해 근본 원인을 파악하고 시정조치를 이행, 재발을 방지하여 지속적으로 품질을 향상할 수 있다.




![Picture5-2](https://github.com/dbsgus16/oss_10/blob/main/Picture5-2.png) 
병이 발생했을 경우, 병 관리: 먼저 제목을 병명으로 설정한다. 상단에 병을 일으킨 해충의 학명을 등록, 치료를 위한 업무 차트를 생성한다. 마지막으로 업무 과제명과 시작 및 종료 날짜, 총 소요 기간과 병에 대한 추가 정보를 입력한다.
이때 사용된 모든 데이터는 인근 지역의 동일 작물 재배지에서 발생 가능한 농작물 병 데이터로 취합, 새로 생성된다. 사용자는 이 새로운 데이터를 이용해 자신의 작물에 병이 발생할 경우 적절히 대처할 수 있다.




![Picture6-2](https://github.com/dbsgus16/oss_10/blob/main/Picture6-2.png)
비료를 살포할 경우: 사용 비료 계열의 이름을 제목으로 설정하고, 정확한 품목명과 밀도, 구성성분, 사용된 살포 기구, 살포 날짜를 기록한다. 사용중인 모든 비료 내역을 한눈에, 단일 플랫폼에서 확인할 수 있다.




활발히 디지털화, 자동화로 전환되고 있는 현재 농업 분야에서 ERPNext는 사용자들에게 농장 관리를 위한 총체적인 솔루션과 사용자 친화적인 인터페이스를 제공한다. 농민들은 관리 비용 및 노동 시간을 절감할 수 있으며 관리 방법이 간편해진 만큼 병 등의 위험 요소 또한 완화할 수 있다. 결과적으로 소규모 및 대규모 농업 기업 전반의 지속 가능한 성장을 주도할 것이다. 




#### 2) Water Analysis 물 분석/ 윤현서


ERPnext는 농업 분야에서 물을 분석하여 물의 탁도, pH, 미량 금속 함유량 등을 추적 및 관리하여 농작물 생산에 영향을 줄 수 있다.


![image](https://github.com/dbsgus16/oss_10/assets/166488062/bfc11cb5-4e6e-4360-99e1-ccf6c635db89)



물의 화학적 성분을 결정하고 이를 ERP 시스템의 위치에 기록하여 작물 관개 공정의 수질을 개선시킬 수 있다. ERPNext를 사용해 샘플을 추적, 관리해 샘플의 수집일, 위치, 샘플 ID 등의 정보를 ERPNext의 재고 모듈에 입력해 샘플을 추적할 수 있다. 그리고 다양한 화학적 물질 또는 미생물 항목을 포함합니다. ERPNext의 항목 관리 기능을 사용하여 각 분석 항목에 대한 정보를 관리 가능하다. 이렇게 나온 데이터들을 ERPNext의 보고서 및 대시보드 기능을 사용하여 시각화할 수 있다.





#### 3) Soil Analysis 토양 분석 / 윤현서


농장이나 농업 기업에서 ERPNext를 이용해 토양 샘플을 수집하고 이에 대한 분석 결과를 기록할 수 있다. 이러한 정보는 토양의 상태를 추적하고 토양 조성물이나 비료 사용량을 최적화할 수 있다. 그리고 작물 생산에 미치는 토양 조건을 파악하는 데에도 도움을 줄 수 있다. 따라서 토양 건강과 농작물 생산성에 긍정적인 영향을 줄 수 있다.


![image](https://github.com/dbsgus16/oss_10/assets/166488062/6ebde5de-3600-486b-8b56-8bdd7c6d392f)


모든 현장 위치에 대해 토양 분석의 등록 번호를 형성 후 모듈에서 현장 위치를 맵핑할 수 있고, 토양 분석 기준을 기록해 함량이나 최소 및 최대값을 출력할 수 있다.


![image](https://github.com/dbsgus16/oss_10/assets/166488062/4420a39f-bcb9-404b-9ee4-01a287118dc8)


ERPNext는 토양을 분석하는 데에 있어서 토양의 질감의 정보도 얻어낼 수 있다. 농업용 토양의 질감은 작물 생산을 위해 토양의 비율이나 특성을 이해할 수 있기 때문에 중요하다. 새로운 토양 텍스처의 세부 정보를 생성 및 저장할 수 있고, 토양 유형을 양토, 모래, 점토, 미사 등과 같이 정의할 수 있다. 그리고 이 토양 유형들의 구성 값과 질감 기준(두께나 유기물)을 분석할 수 있다.




#### 4) Weather Record 날씨 기록 / 윤현서


![image](https://github.com/dbsgus16/oss_10/assets/166488062/9c162ed8-1434-4f31-9fdb-0a3af83767a0)


농업 분야에서 일기예보는 모든 작물 생성에 영향을 끼치기 때문에 매우 중요하다. 그렇기에 ERP 시스템을 이용해 작물 기상 분석을 이해하고 기록할 수 있다. 새로운 날씨 정보를 작성해 위치를 맵핑할 수 있고, 모든 날의 날씨와 정보 및 출처가 언급되어 있다. 그리고 습도, 기압, 이슬점, 강수량, 온도 등의 날씨 매개변수를 기록할 수 있다.




#### 5) Sales/Purchase 공급업체 동향 분석, 가격


농업 분야에서의 거래 과정에서 ERPnext를 활용하면 공급 업체 또는 제품이나 서비스를 판매하는 사람의 세부정보, 상품의 견적 요청, 구매 주문을 저장하고 관리하며, 각 공급업체에 대한 기본 지불 계좌를 관리할 수 있다. 이를 통해 구매자의 구매 패턴을 인지하고 이에 대해 지속적인 거래에서 변경된 사항에만 빠르게 대비하는 등 효율적으로 대응할 수 있다.





공급자의 이름이나 연락망 등의 기본 정보, 대금 지급 날짜, 비용 청구 주소, 그리고 각 상품의 품목 세부정보, 상품의 총 가격등 사용자가 원하는 대로 수동으로 구매 주문 송장을 작성하거나 작성한 송장을 기본값으로 지정 함으로서 이후 모든 거래에서 자동으로 같은 가격 항목을 구성할 수 있다, 자동으로 송장의 인쇄 템플릿을 작성해 주기도 한다. 


![A](https://github.com/dbsgus16/oss_10/assets/165997477/3286ae2f-4d47-4a19-aaeb-4d7d29552037)


또한 단일 통화가 아닌 어떤 통화로든 구매 주문 송장을 보낼 수 있고 비용을 추가하면 시스템에서 이를 기본 통화로 변환하는 것도 가능하다. 여러 통화로 이루어진 금융 거래가 가능하고 이를 기록한 보고서를 열람할 수 있다.




#### 6) Billing/Pricing 청구서, 가격 책정


ERPnext로 구매 주문 송장뿐만 아니라 매출 계산서의 자동 생성 템플릿의 작성도 가능하다. 기본적으로 여러 통화를 통한 금융 거래 등 위에서 언급한 구매 주문 송장 작성 시 가능한 요소들을 매출 계산서에 적용하는 것 또한 가능하다.


![B](https://github.com/dbsgus16/oss_10/assets/165997477/72b73c7b-c805-45d1-b598-3a51787f311c)


매출 계산서에 고객 이름, 구매 날짜 및 배송 날짜를 정해놓거나, 사전 정의된 품목 세부정보(품목 코드, 이미지, 수량, 할인, 중량, 금액)를 기재하며, 총 수량과 가격에 적용된 로얄티 등을 자동으로 반영하는 것이 가능하다.
상품 판매 시 그에 대한 세금이 붙게 되는데, 이를 관리하기 위해 세금 목록 문서 템플릿을 만드는 것이 가능하다. 여기에는 제목, 회사 및 상품에 붙은 각 세금의 유형 세부 정보 등을 추가할 수 있다.


상품에 대한 할인을 적용할 때 고객의 주문 선호도를 높이기 위해 일부 가격 책정 규칙 기준(품목, 고객, 공급자, 수량, 적용 대상, 유효성 등)또는 매수/매도 기준 및 마진 필드 등의 조건을 지정하거나 규칙 적용의 우선순위를 설정하는 것도 가능하다.


판매 완료 후 고객의 주문 상태나 배송상태 관리 및 조회가 가능하며, SMS 또는 이메일을 통해 고객에게 매출 계산서를 전송하고, 대금 지불 상태(부분 지불, 지불, 대기 중)를 조회하여 매출 계산서가 전송된 고객 중 미수금 고객의 비용 지급 여부를 추적할 수 있다.





#### 7) Manage Crops 작물 관리 / 홍예준
(ERPNEXT에 로그인하여 대시보드에서 관리 항목을 선택 -> 추가 버튼을 클릭 -> 보이는 양식에 작물의 종류, 품종, 재배 일정 등의 정보를 입력 -> 저장 버튼 클릭)


작물의 종류, 품종, 재배 일정 등의 정보를 바탕으로 성장 상태, 건강 상태 와 같은 필수적인 사항에 실시간으로 모니터링합니다.
수확 플랜을 계획하고 수확된 작물의 양과 품질을 기록하면서 이에 사용된 비료 및 농약의 종류, 양, 사용 일정 등도 관리합니다.





#### 8) Crop Cycle 작물 주기 관리 / 홍예준
(대시보드에 주기관리 항목을 선택 -> 주기(생애) 추가 버튼을 클릭 -> 보이는 양식에 작물의 종류, 주기 이름, 시작일 및 종료일 등의 필요한 정보를 입력 -> 저장 버튼 클릭)

![B](https://github.com/dbsgus16/oss_10/blob/main/%EC%9E%91%EB%AC%BC%EC%A3%BC%EA%B8%B0%EA%B4%80%EB%A6%AC.PNG)

성장에 영향을 미치는 생육 환경(온도, 습도, 토양 조성 등)을 조건에 맞게 원격으로 조절합니다. 
나아가 토양 소진을 방지하고 작물 생산성을 극대화하기 위해 작물 회전 일정을 관리합니다.
이렇듯 작물 주기 관리는 작물의 종류별로 생애 주기와 관련해 적절한 보수 및 유지 관리 일정을 체계화합니다.




#### 9) Location Management 위치 관리 / 홍예준
(대시보드에 위치관리 항목을 선택 -> 위치(심어진 곳) 추가 버튼을 클릭 -> 보이는 양식에 작물의 종류, 위치 이름, 좌표 등의 필요한 정보를 입력 -> 저장 버튼 클릭으로 정보 저장)


각 작물이 심어진 위치를 추적하고 관리하여 생산성을 최적화하고 효과적인 작업에 뒷받침합니다.
작물간의 배치를 고려해 작물 간의 경쟁을 최소화하고 자원이 효율적으로 사용될 수 있도록 서포트합니다. 
특정 작물을 식별하고 위치를 쉽게 찾을 수 있는 방법 또한 제공합니다.
