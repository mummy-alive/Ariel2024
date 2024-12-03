# How to execute

1. [Calibrating & Binning Astronomical Data](https://www.kaggle.com/code/gordonyip/update-calibrating-and-binning-astronomical-data/notebook) 에서 Trainset, Testset raw data를 처리하여 다운받는다.
2. /data/ 폴더를 만들고, 다운받은 `trainset.npy`, `testset.npy`을 저장한다.
3. /output/ 폴더를 만든다.
4. `CNN1D.ipynb` 실행
5. `CNN2D.ipynb` 실행
6. /output/에 저장된 두 모델과 완성된 전처리 dataset을 Kaggle에 업로드 한 후, `model_concat.ipynb`를 Kaggle에 올린다.
7. `model_concat.ipynb`를 실행한 후, Kaggle에 저장
8. [Ariel 2024 Data Challenge 페이지](https://www.kaggle.com/competitions/ariel-data-challenge-2024)에서 저장된 notebook을 제출한다. (결과출력까지 약 50분 소요)

*전처리/ model train 결과물은 제 [Kaggle Dataset](https://www.kaggle.com/datasets/mummyee/testset-2d/data)에서 별도로 다운받을 수 있습니다.*


##참고문헌
[1] [Kai Hou Yip, Lorenzo V. Mugnai, Rebecca L. Coates, Andrea Bocchieri, Andreas Papageorgiou, Orphée Faucoz, Tara Tahseen, Virginie Batista, Angèle Syty, Arun Nambiyath Govindan, Sohier Dane, Maggie Demkin, Enzo Pascale, Jean-Philippe Beaulieu, Quentin Changeat, Pierre Drossart, Billy Edwards, Paul Eccleston, Clare Jenner, Ryan King, Theresa Lueftinger, Nikolaos Nikolaou, Pascale Danto, Sudeshna Boro Saikia, Luís F. Simões, Giovanna Tinetti, and Ingo P. Waldmann. NeurIPS - Ariel Data Challenge 2024. NeurIPS - Ariel Data Challenge 2024. Kaggle.](https://www.kaggle.com/competitions/ariel-data-challenge-2024)\
[2] [Calibrating and Binning Astronomical Data](https://www.kaggle.com/code/gordonyip/update-calibrating-and-binning-astronomical-data/notebook)\
[3] [GordonYip, Angele Syty, Orphée Faucoz, Tara Tahseen, Virginie Batista - Host Starter Solution](https://www.kaggle.com/code/gordonyip/host-starter-solution)\
[4] [NeurIPS Ariel 2024 - Starter](https://www.kaggle.com/code/hugowjd/neurips-ariel-2024-starter)
