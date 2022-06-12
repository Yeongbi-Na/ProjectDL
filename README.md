## DeepLearning Project (2021-1)

 딥러닝 프로젝트
"카페 내부 이미지 클러스터링을 통한 카페 분류"</br></br>
👋 My role: 카페 내부 이미지 수집, Pretrained model 활용 등
</br></br>

<h2>Purpose </h2>
요즘 카페는 단순히 커피를 마시는 공간 그 이상의 의미</br></br>
개인마다 선호하는 카페 분위기가 있으며 이를 찾기 위해 네이버 지도, 블로그 리뷰 등을 탐색하며 많은 시간이 소요됨</br></br>
→ 분위기(내부 인테리어)에 따라 카페를 분류해 취향에 맞는 카페 추천</br>

</br>
<h2>Survey </h2>
군집 모델의 실루엣 계수 값이 타당했지만 모델의 군집 결과가 설정한 의도에 적합한지는 다른 문제</br></br> '실제 분위기에 따라 모델이 분류했는지' 검증하기 위해 설문조사를 실시</br></br>

#### <설문조사 방법>
성능이 가장 우수했던 DEC모델 군집 결과에 대한 52명에 대해 두가지 방법으로 설문조사를 진행</br>
1. 동일 군집 내에서 추출한 카페 이미지에 대한 유사도 점수 *같은 카페 들어가지 않도록 설정</br></br>
2. 서로 다른 군집에서 추출한 카페 이미지에 대한 유사도 점수</br></br>

#### <결과>
1. 동일 군집의 사진에 대해 3.52, 3.18, 3.51, 2.58의 유사도 점수 </br></br>
2. 서로 다른 군집의 사진에 대해서는 2.31의 유사도 점수</br>


![report_Korean pdf_page_01](https://user-images.githubusercontent.com/61492320/173224597-86c7e8e1-e69e-4b9b-827c-a220fe192c70.jpg)
![report_Korean pdf_page_02](https://user-images.githubusercontent.com/61492320/173224598-7d4ca74c-7112-423a-af87-2c0671977e30.jpg)
![report_Korean pdf_page_04](https://user-images.githubusercontent.com/61492320/173224601-006ace82-ad32-49a2-bbf8-66887b9e39b0.jpg)
![report_Korean pdf_page_06](https://user-images.githubusercontent.com/61492320/173224604-7c19780c-16e9-447c-af58-937313cf487d.jpg)
![report_Korean pdf_page_07](https://user-images.githubusercontent.com/61492320/173224607-e6044a11-cd02-4732-9aaf-6e6941ab5851.jpg)
![report_Korean pdf_page_08](https://user-images.githubusercontent.com/61492320/173224609-8fc21bf3-e667-4440-9999-32751e24f016.jpg)
![report_Korean pdf_page_09](https://user-images.githubusercontent.com/61492320/173224610-598df946-275c-4fc2-b9b8-f1c6839ff716.jpg)
![report_Korean pdf_page_10](https://user-images.githubusercontent.com/61492320/173224612-5462a8f1-2468-40a9-b81b-12df7144ce0f.jpg)
![report_Korean pdf_page_11](https://user-images.githubusercontent.com/61492320/173224614-9a9e8273-34dd-480d-8862-6db6f6492523.jpg)
![report_Korean pdf_page_12](https://user-images.githubusercontent.com/61492320/173224616-ca8f9fdd-2db0-4d2f-be65-909a5367c992.jpg)
![report_Korean pdf_page_13](https://user-images.githubusercontent.com/61492320/173224579-59adf172-c0d6-479a-b326-079ff42683a1.jpg)
![report_Korean pdf_page_14](https://user-images.githubusercontent.com/61492320/173224581-0f19a9c6-49e5-49d0-a1c8-e5d9ee4447a0.jpg)
![report_Korean pdf_page_15](https://user-images.githubusercontent.com/61492320/173224582-f88e8d50-a27a-41a6-859b-8463e64b8135.jpg)
![report_Korean pdf_page_16](https://user-images.githubusercontent.com/61492320/173224584-522d94a0-1617-400c-9d37-d05787e9476a.jpg)
![report_Korean pdf_page_17](https://user-images.githubusercontent.com/61492320/173224585-3409fcf2-9822-4545-af71-1c7491d6b400.jpg)
![report_Korean pdf_page_18](https://user-images.githubusercontent.com/61492320/173224586-864e1569-e84d-4944-90a3-d1996ccb0088.jpg)
![report_Korean pdf_page_19](https://user-images.githubusercontent.com/61492320/173224587-13b7ea8d-f070-4f76-9e54-4dd79a33366f.jpg)
![report_Korean pdf_page_20](https://user-images.githubusercontent.com/61492320/173224589-3b32cd79-f4fa-43cf-81d1-4f2202e852d1.jpg)
![report_Korean pdf_page_21](https://user-images.githubusercontent.com/61492320/173224590-a91601ef-3279-439b-a92e-c6d4bf41e1be.jpg)
![report_Korean pdf_page_22](https://user-images.githubusercontent.com/61492320/173224592-2f96bcc4-f918-4e11-8a09-c8c51027db23.jpg)
![report_Korean pdf_page_23](https://user-images.githubusercontent.com/61492320/173224593-b631be00-4794-499f-9f2d-5a81eb41eaaf.jpg)
![report_Korean pdf_page_24](https://user-images.githubusercontent.com/61492320/173224595-97748ac2-e7a3-493b-8bbc-52fccb4996e9.jpg)
![report_Korean pdf_page_25](https://user-images.githubusercontent.com/61492320/173224596-45884fa9-ed5c-467e-998f-fc00c8b3aefb.jpg)

