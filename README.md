# Research Project : Memory Reactivation & Prunning

## Index
  - [Authors](#authors) 
  - [About](#about) 
  - [Overview](#overview) 
  - [Files](#files)
  - [License](#license)

## Authors
- **Taehoon Kim**, & Ghootae Kim
- Deep Memory Lab, Cognitive Science Research Group, Korea Brain Research Institute

## About
- 이 Repository는 행동 인지 실험의 데이터 분석 작업물을 담고 있습니다.
- 실험 프로그램 코드, 개별 참가자의 원본 데이터는 포함되어 있지 않습니다. 
- 분석은 R과 R studio를 통해 수행되었으며, 분석 코드 및 결과는 **reactMem_Results.html** 를 다운로드받아서 확인할 수 있습니다. 
- 다른 파일에 대한 정보는 아래 **FILES**에서 확인할 수 있습니다.

## Overview
- Kim et al., 2017. 관련 행동 연구. (Kim, G., Norman, K. A., & Turk-Browne, N. B. (2017). Neural differentiation of incorrectly predicted memories. Journal of Neuroscience, 37(8), 2022-2031.)
- 연합된 context에 의한 memory reactivation과 reactivated/predicted event 간의 불일치가 이전에 연합된 기억을 약화시키는지 행동 실험을 통해 검증
- 반복을 통해 연합된 A-B 시퀀스에서 A이후 B'가 주어진 경우(reactivation + prediction error), A-B Association Memory의 약화 확인.

## Files
- reactMem_Results.Rmd : 데이터 분석을 위한 RMarkDown source code
- reactMem_Results.html : 분석 코드 및 결과, 다운로드 후 확인 가능
- data : raw data 폴더, 비어있음
- image : 결과 요약 관련 이미지
- KBRI2021.reactMem.R.thk.pdf : 프로젝트 관련 로그

## License

```
MIT License

Copyright (c) 2021 Kim, Taehoon

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

```
