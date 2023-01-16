#### Medical MNIST

* Medical MNIST 데이터셋은 58,954개의 다양한 의료 이미지로 구성되어 있습니다.
* 총 6개의 클래스(class)로 구성됩니다.

<pre>
0. 복부 CT (Abdomen CT)
1. 유방 MRI (Breast MRI)
2. 흉부 X-ray (Chest X-Ray)
3. 흉부 CT (Chest CT)
4. 손 X-ray (Hand X-Ray)
5. 손 CT (Hand CT)
</pre>

* 각 이미지는 64 X 64 X 1 크기를 가집니다.
* 데이터셋 폴더 구성은 다음과 같습니다.

<pre>
MedicalMNIST/
    train/ # 학습 이미지가 담긴 폴더입니다.
        AbdomenCT/
        BreastMRI/
        ChestCT/
        CXR/
        Hand/
        HeadCT/
    test/ # 테스트 이미지가 담긴 폴더입니다.
        AbdomenCT/
        BreastMRI/
        ChestCT/
        CXR/
        Hand/
        HeadCT/
</pre>
