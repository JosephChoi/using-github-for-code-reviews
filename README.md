깁헙으로 코드리뷰 하기(Using github for code reviews)
=====================================================

깃헙을 코드 리뷰에 활용하는 방법을 설명하기 위한 리파지터리입니다.  

대부분은 `Pull Requests`를 사용해 코드 리뷰를 할 수 있으며,  
기존에 존재하는 리파지터리가 없거나 개인이 진행하는 코드인 경우라면, 커밋 히스토리를 활용하는 방법이 있습니다.


## Pull Requests로 리뷰하기
공동 작성하고 있는 코드이거나, 이미 코드가 있는 과제에 적합합니다.

>1. 리뷰어(Reviewer)는 먼저 원본 리파지터리를 준비합니다.
>2. 리뷰받는 사람(reviewee)은 원본 리파지터리를 `Fork`합니다.
>3. 리뷰받는 사람은 작업을 마친 후, 커밋한 코드를 `Pull Requests`합니다.
>4. 리뷰어는 [Pull Requets 메뉴](https://github.com/ohgyun/using-github-for-code-reviews/pulls)에서 요청온 코드를 리뷰해줍니다.
>
> (Tip)  
> 팀 내 공동 과제이거나 교육을 위한 과제처럼 여러 사람을 위한 리뷰라면,  
> 받은 요청을 커밋하지 않고 바로 요청을 Close합니다.  
> 리뷰받는 사람은 close 된 다른 사람의 리뷰 히스토리를 참고해 학습할 수 있습니다.


## Commits 히스토리로 리뷰하기
개인이 혼자 진행하는 과제 또는 프로젝트인 경우에 적합하며,  
[Commits 메뉴](https://github.com/ohgyun/using-github-for-code-reviews/commits/master)의 커밋 히스토리에 댓글을 다는 방식으로 리뷰합니다.

>1. 리뷰받는 사람이 직접 자신의 리파지터리를 생성하고 작업합니다.
>2. 리뷰받을 코드를 커밋하고, 리뷰어에게 리뷰받을 [커밋 히스토리 링크](https://github.com/ohgyun/using-github-for-code-reviews/commit/8a85b15805237214aea83a1131f0548b3b69a2d8)를 전달합니다.
>3. 리뷰어는 Commits 히스토리 페이지에서 코드를 리뷰해줍니다.

> (Tip)  
> Commits 메뉴에서는 각 커밋에서 변경한 코드만 볼 수 있습니다.  
> 작업한 전체 내용을 리뷰 받으려면, 작업이 최종 완료된 후에 커밋합니다.
