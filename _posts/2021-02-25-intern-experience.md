---
title: Common computer 2020 winter internship
layout: post
summary: 2020년 겨울 커먼컴퓨터 인턴
author: fpem123
date: '2021-03-22 00:00:00'
category: experience
keywords: experience, internship, common computer
usemathjax: true
thumbnail: /assets/img/projects/comcom_intern/image10.png
permalink: /blog/comcom-internship/
---

### Common computer 2020 winter 인턴십 후기

 대학도 마치고 할 것 없던 2020년 겨울, 코로나 바이러스로 인해 아르바이트 하나 구하기 어렵던 시기에 할 일이 생겼었습니다. 그건 바로 운 좋게 합격한 Common computer 인턴십! 그 인턴십에 대한 후기입니다~

<hr>

### 🤔 어떻게 지원했을까? 
 학교 현장실습 인턴십 홈페이지를 찾아보던 중 좋은 조건, 재미난 활동, 다양한 사업을 하는 기업이 눈에 띄었고 바로 지원해버렸습니다. 그곳이 바로 커먼컴퓨터! 새롭고 좋은 경험을 얻을 수 있을 것 같았습니다.
 인턴십 지원 후 온라인 과제가 나왔는데, Docker와 Kubernetes를 이용한 간단한 프로젝트 제작하기였습니다. 지금까지 학교 수업만 들었던 저에겐 처음 접해본 기술이지만, 유튜브 영상과 회사에서 제공해 주신 문서들을 참고하여 며칠간 뚝딱뚝딱 만들었습니다. 그리고 추가적인 면접을 진행하였고 마음을 졸이고 있던 사이... 짠! 하고 붙었습니다! 👏👏👏
 
<center><img src="https://images.velog.io/images/fpem123/post/ed796666-175d-4775-859f-b93e5d8dbaf0/image10.png" width="80%"></center>

<hr>

### 🔮 Ainize!


<center>
<img src="https://images.velog.io/images/fpem123/post/2128ac69-0756-4c3a-af11-a422b6a8a94a/image8.png" width="80%">
<br>
Ainize 사이트의 모습
</center>

 커먼컴퓨터는 신기한 플랫폼을 운영하고 있습니다. 그건 바로 Ainize! Ainize의 개발 모토는 개발자들이 자유롭게 뛰어놀 수 있는 공간 제공해 주는 것이라고 합니다. 그 모토에 맞게 Ainize는 Web application, API, 머신 러닝 프로젝트를 빌드하고 배포할 수 있는 자유로운 환경을 제공합니다. 다만, Ainize는 GitHub 리포지토리 내의 Dockerfile을 읽어 프로젝트를 빌드 하는 방식이기에 프로젝트를 올리기 위해서는 Docker를 알아야 합니다. 하지만, Docker 기술은 빌드를 편리하게 하고 다양한 환경에서 작업하기 위한 것! Docker의 D도 모르던 저도 금방금방 쑥쑥 배워나갔습니다.🦾

<center>
<img src="https://images.velog.io/images/fpem123/post/14a26684-2a15-44a0-ad22-3922969e3126/image3.png"  width="80%">
<br>
다양한 분들이 Ainize에 올린 프로젝트들
</center>

<br>

 Ainize는 개발자들에게 GPU를 사용할 수 있는 환경도 지원해 줍니다! Dockerfile의 베이스 이미지(FROM)를 Cuda가 있는 이미지로 작성해 주면, 프로젝트에 짜잔 하고 GPU가 할당됩니다(cuda 11.0 이상의 이미지는 NVIDIA RTX 30시리즈와 NVIDA A100 에서만 동작하기 때문에 아직 GPU를 할당받을 수 없습니다…!). 좋은 GPU를 소유하지 않아도 Ainize를 사용하면 GPU 프로젝트를 손쉽게 만들 수 있습니다.
  저는 인턴으로서 이 Ainize를 사용하는 Ainizer가 되었습니다. 그럼 이 Ainizer가 무엇이냐? Ainize와 User의 합성어로, 직역하자면 Ainize를 사용하는 사람들이란 뜻이고, Ainizer의 주 역할은 Ainize에서 AI 최신 기술을 접하고, 실행해보고, 네트워킹에 참여하며, AI 오픈소스 프로젝트들을 찾아 Ainize에 배포하는 것입니다. 그럼 Ainizer는 인턴만 할 수 있느냐? 아닙니다! 여러분 모두 Ainizer가 되실 수 있습니다~.

<hr>

### 그럼 무엇을 했을까?

  저는 커먼컴퓨터의 인턴이자 Ainizer로서 Ainize 플랫폼을 사용해보고 다양한 프로젝트를 배포하는 것이 주 활동이었고, 특히 Ainize의 GPU를 사용할 수 있는 환경이라는 강점을 살려 머신 러닝 프로젝트를 주로 배포하였습니다. 그리고 작업을 위한 장비! 무려 Mac book을 지원받았습니다!!!
  처음엔 셀레니움을 활용한 워드 클라우드 앱을 배포했습니다. 셀레니움을 사용하기 위해선 크롬과 크롬 드라이버를 설치해야 하지만, Docker에 명령어 몇 줄이면 바로 해결! 성공적으로 배포했습니다. 🥳

<center>
<i>
<img src="https://images.velog.io/images/fpem123/post/51433409-8d0d-4aa8-91b5-725a1a6e90a8/image9.png"  width="80%">
<br>

Project #1: 간단한 유튜브 워드클라우드 ([link](https://master-word-cloud-fpem123.endpoint.ainize.ai/))

</i>
</center>

<br>

  Ainize 플랫폼과 Docker에 익숙해지던 찰나에 회사의 향후 프로젝트! Ai writer와 NLP 프로젝트를 위한 작업이 시작되었고 저와 다른 인턴분들은 GPT-2 프로젝트를 위한 활동과 작업을 시작하게 되었습니다.
  
 먼저, GPT-2 익숙해지기! Hugging face🤗의 다양한 Public 모델을 사용해보고 Ainize에 업로드하여 GPT-2 모델을 알아보는 시간이었습니다.
 그리고, GPT-2 Fine tuning! 먼저 한 작업은 이미 완성된 모델을 사용해보는 것이었다면, 이번엔 저희가 모델을 직접 tuning 하는 작업이었습니다. Kaggle과 GitHub의 다양한 오픈 데이터를 모아 Fine-tuning을 하였습니다. 그런데 이럴 수가! 로컬에선 GPU가 모자라서 돌아가지 않습니다... ㅠ.. Fine tuning을 하는데 요구사양이 좀 있었습니다😰. 그래서 Google의 Colab에서 Fine-tuning을 하였습니다. Fine-tuning을 몇 번 해보던 그 순간! 문제가 생겼습니다. 구글 드라이브가 지원하는 공간은 15GB, GPU memory는 13GB 뿐이라는 점입니다. 여러 모델을 만들어보고 싶었지만, GPT-2 기본 모델의 사이즈는 무려 500mb, 거기에 생성되는 Check point 사이즈까지 합치면… 용량이 많이 부족합니다. 그리고 GPT-2 기본 모델만 만들어볼쏘냐! 거대한 GPT-2 모델! 무려 3GB의 크기를 자랑하는 GPT-2 Large 모델을  Fine-tuning 해보려 했지만, Colab에선 GPU 부족으로 아예 돌아가지 않았습니다.🥺
  하지만, 이런 고민들은 한 번에 싹 해결! 회사에서 무려 A100 GPU를 사용할 수 있는 서버를 지원해 주셨습니다! 그렇게 A100 서버에서 GPT-2 Large 모델을 다양한 데이터로 Fine-tuning 해보았습니다. 저는 주로 Script 데이터를 사용해서 tuning 했는데 생각보다 웃긴 결과들이 많이 나왔습니다. 🤣


<center>
<i>
<img src="https://images.velog.io/images/fpem123/post/fde426cc-439e-467f-9859-0a956b09fcdf/image11.png" width="80%">
<br>

Project #5: GPT-2 SpongeBob script ([link](https://master-gpt2-spongebob-fpem123.endpoint.ainize.ai/))

<br>

<img src="https://images.velog.io/images/fpem123/post/a9eb00ca-eda9-41fb-85b2-d7b790af33e6/image5.png" width="80%">
<br>

Project #6: GPT-2 Simpsons script ([link](https://master-gpt2-simpsons-fpem123.endpoint.ainize.ai/))

<br>

<img src="https://images.velog.io/images/fpem123/post/19bbaf27-d9c3-45d4-8177-f4b4eb1a1b65/image1.png" width="80%">
<br>

Project #11: GPT-2 Futurama script ([link](https://master-gpt2-futurama-fpem123.endpoint.ainize.ai/))
</i>
</center><br>

  여러 데이터를 tuning을 하던 중, 이상한 점이 발견되었습니다. 모델이 가끔 결과를 이상하게 만들어내는 문제가 생겼습니다. 글 중간중간 개행이 많이 일어나는 등의 상황이 마구마구 나왔습니다. 회의를 진행해본 결과 문제는 전처리! NLP 관련 작업들은 전처리가 거의 필수로 필요하던 것이었습니다. 그런데 전처리를 하지 않았던 게 문제였습니다. 그래서 GPT-2의 데이터 전처리에 대해 조사해보았는데 보통의 NLP 작업들처럼 전처리하면 된다는 점을 알아내어, 전처리하여 다시 한번 GPT-2 모델을 tuning 하였습니다. 그리고 나오는 결과는 눈에 띄게 좋은 결과를 보여주었습니다!

<center>
<i>
<img src="https://images.velog.io/images/fpem123/post/473afaf5-46c7-48f4-a8a4-1930f950a9f3/image7.png" width="80%">
<br>

Project #12: GPT-2 FairyTales ([link](https://master-gpt2-fairy-tales-fpem123.endpoint.ainize.ai/))

</i>
</center><br>

  많은 모델을 만들어보고 Ainize에 업로드하다 보니 어느덧 2달의 짧은 인턴 기간이 끝나가게 되었습니다. 하지만 완전한 끝은 아닌 법, 인턴 마지막 날에는 디자인 스프린트가 하루 종일 진행되었습니다. 처음엔 어떻게 진행되는지 궁금하였는데, 막상 해보니 엄청 즐거운 활동이었습니다. 많은 직원분들과 함께 모여 회사 프로젝트가 나아가야 할 방향과 모두의 아이디어 공유와 디자인 구상을 하였던 뜻깊은 시간이었습니다.
  어느 식으로 진행되었냐면, 먼저 프로젝트에 내재된 문제점을 생각한 뒤, 어떤 문제에 집중할지 투표를 진행하였고 Crazy 8에 대한 설명을 들었습니다. Crazy 8은 문제점들에 대해 1분 만에 문제점에 대한 솔루션을 구상하고 종이에 간단한 스케치를 만드는 걸 8번 반복하는 방법이었습니다. 그리고 저는 “사용자들이 제품을 사용하기 이전, 제품을 파악하고 배우게 할 수 있을까?” 를 고민하는 그룹에 할당되었고, 발견한 문제점들 중에서 어떻게 하면 사용자들이 “머신러닝 관련 용어를 빠르게 이해하고 습득할지”와 “좋은 데이터가 왜 필요한가 알려주기”를 중점으로 작성해보았습니다.

<center>
<img src="https://images.velog.io/images/fpem123/post/84dbd00c-2b86-4350-b0db-0d4094e1b4e8/image2.jpg" width="80%">
<br>
제가 작성한 Crazy 8

</center><br>


  Crazy 8 작성 후, 그룹원들끼리 작성한 아이디어를 공유하였고 모인 정보를 토대로 설루션 스케치를 작성했습니다. 솔루션 스케치는 Crazy 8과 비슷해 보일 수 있지만, 조금 달랐습니다. Crazy 8이 짧은 시간 동안 여러 개의 아이디어를 만드는 것이었다면, 솔루션 스케치는 하나의 솔루션을 더 많은 시간 동안 모두가 알아볼 수 있도록 세세하게 작성하는 것이었습니다. 그래서 저는 이번엔, “좋은 데이터가 왜 필요한가 알려주기”에 초점을 맞춤과 더불어 데이터 습득, 전처리, 모델 획득을 더 쉽게 할 수 있는 디자인을 생각해 보았습니다. 그때 떠오른 것이 바로 구글 플레이 스토어였고 비슷한 디자인으로 작성해보았습니다. 그리고 각자 자신이 작성한 솔루션 스케치를 설명하고 투표하는 시간을 가졌습니다.

<center>
<img src="https://images.velog.io/images/fpem123/post/17184137-2c5c-4248-8c3d-5545ab7b178f/image4.jpg" width="80%">
<br>
제가 작성한 솔루션 스케치

<br>

<img src="https://images.velog.io/images/fpem123/post/437cec2b-c716-492f-a867-cc2a2b3f98c7/image6.jpg" width="80%">
<br>
솔루션 스케치 투표하는 사진*
</center><br>


  저는 지금까지 여러 디지털 아티팩트가 만들어지는 과정 중 디자인 부분은 디자이너와 경영진들이 먼저 구상해오고 프로그래머들이 그걸 따라 만드는 형태인 다소 따분한(?) 형태인 줄 알았습니다. 하지만 개발자, 디자이너, 재무회계사 할 것 없이 모두 모여 서로의 생각과 아이디어를 공유하는 활동을 하니 신선한 충격을 받았습니다. 오히려 이런 방식이 제품을 더 좋은 방향으로 만들 수 있고 향후 문제를 방지할 수 있는 좋은 방식이란 생각을 가지게 되었습니다.

<hr>

### 마지막으로 느낀점! 
  저는 이번 인턴 경험이 정말 좋았습니다. 저는 그동안 학교 수업만 들었을 뿐, 현장에 대한 경험들이 전무하였고 또 한편으론 두려웠었습니다. 과연 내가 잘 할 수 있을까? 과연 책이 아닌 실무에선 무슨 작업들을 하고 어떻게 작업들을 하는 거지? 하는 고민들도 있었고 현장은 멀게만 느껴졌었습니다. 하지만, 이번 인턴 경험을 통해 그런 고민들은 저 멀리! 많이 사라졌습니다. GPT-2 모델 튜닝 결과가 이상하게 나왔을 때, 작업 서버가 다운되었을 때 같은 어려운 것이 있으면 직원분들과 회의와 소통을 통해 해결법을 찾아내고 배우며 발전할 수 있는 좋은 경험이었고, Docker와 다양한 기술을 배울 수 있던 재미난 경험이었습니다. 이번의 경험들이 미래 제가 성장할 수 있는 원동력이 되어줄 수 있을 것이라 믿고, 만약 커먼컴퓨터에 지원에 보고 싶은 분이 계시다면 지원하는 것을 추천하고 싶습니다.

<br>
<hr>
