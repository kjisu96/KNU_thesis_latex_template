# KNU_thesis_latex_template

Kyungpook National University (KNU) Thesis/Dissertation LaTeX Template.



경북대학교 학위 논문 LaTeX 양식입니다. 테스트 환경은 Windows 11, Tex Live 2024 이며 2025년 1월 기준 양식으로 작성했습니다. 컴파일 환경은 Visual Studio Code의 LaTeX Workshop extension에서 `latexmk`를 사용했습니다.
석사 논문으로도 편집 가능하나, 박사 논문 양식으로만 테스트 완료 했습니다. Overleaf는 테스트 해보지 않았으며 제가 사용하지 않기 때문에 컴파일 등에 대한 질문을 하셔도 도움이 되지 못할 것 같습니다.



경북대학교 학위논문 서식(2025년 1월 기준)은 겉표지, 인준서에 대한 서식만 지정하고 본문에 대한 서식은 따로 지정하지 않고 있습니다. 그러니 본문 양식은 자유롭게 수정하여 사용하시면 됩니다. 그리고 학교에서 제공하는 학위 논문 양식은 MS Word와 HWP 2가지 버전이 있는데, 국문 초록의 경우 HWP 파일에만 포함되어 있어서 필수가 아닌 것으로 보입니다. 일단 본 양식에는 영문 초록, 국문 초록 모두 포함되어 있으니 필요에 따라 제외/포함하시면 됩니다.



본 양식에서 사용되는 개인 정보는 대부분 tex 파일에서 수정하도록 하고자 했으나 일부는 `knu-ucs.cls` 파일에서 수정을 해야 합니다. 장담은 못하지만 컴파일 문제 발생 시 issue에 업로드 하시면 최대한 같이 봐드리겠습니다. (가능한...)

감사합니다.



> **Acknowledge**
>
> 본 양식은 @lonelywing 님의 POSTECH 학위 논문 LaTeX 양식을 바탕으로 @seonho 님의 겉표지, 인준서 양식을 합쳐 만들었습니다. 공유 감사드립니다.
>
> https://github.com/lonelywing/POSTECH_thesis_template_latex.git
>
> https://github.com/seonho/KNU-Thesis.git





+++



This repository provides the LaTeX template for thesis and dissertation formatting at Kyungpook National University. The template has been tested in a Windows 11 environment using TeX Live 2024 and is based on the official formatting guidelines as of January 2025. While it can be adapted for master's theses, testing has only been conducted for doctoral dissertations. This template has not been tested on Overleaf, and as I do not use the platform, I am unable to provide support for related compilation issues. 

The official thesis formatting guidelines issued by Kyungpook National University (as of January 2025) specify formatting requirements only for the cover page and approval sheet, without imposing specific formatting rules for the main text. Therefore, users are free to modify the main text formatting as needed. The university provides official thesis templates in both MS Word and HWP formats. Notably, the Korean abstract is only included in the HWP template, suggesting that it may not be mandatory. This LaTeX template includes both English and Korean abstracts, which can be included or excluded as needed.

Most personal information fields in this template can be edited directly in the `.tex` files; however, some modifications must be made within the `knu-ucs.cls` file. While I cannot guarantee a resolution for all compilation issues, I encourage users to report problems via the issue tracker, and I will assist as much as possible.

Thank you.
