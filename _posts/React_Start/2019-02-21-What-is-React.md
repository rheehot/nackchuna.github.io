---
layout: post
comments: true
categories: React&nbsp;Start
---

# React란?
### 프론트엔드 라이브러리 리액트

&nbsp;

리액트는 인기 있는 프론트엔드 라이브러리로 "컴포넌트"라는 개념에 집중이 되어 있는 라이브러리입니다. 컴포넌트는 간단히 이야기하면 데이터를 넣으면 우리가 지정한 인터페이스를 조립해서 보여줍니다.

사실 웹사이트를 만들기 위해선 프론트엔드 라이브러리 없이도 만들 수 있습니다. HTML과 CSS를 사용해서 만들면 되죠.

이런 단순한 웹페이지가 아니라 유저인터페이스를 동적으로 나타내기 위해서는 정말 많은 상태 관리를 해줘야 합니다. 프로젝트 규모가 커지고, 정말 다양한 유저인터페이스와 인터랙션을 제공하게 된다면 많은 DOM요소들을 직접관리하고 코드를 정리하는 것은 매우 힘든 일일 것입니다.

웹 개발을 할 때 귀찮은 DOM관리와 상태값 업데이트 관리를 최소화하고, 오직 기능개발 그리고 사용자 인터페이스를 구현하는 것에 집중할 수 있도록 하기 위해서 만들어 진 것이 프론트엔드 라이브러리 이고, 그 중에 하나가 페이스북에서 만든 리액트입니다.

&nbsp;

### 리액트가 만들어진 이유

&nbsp;

페이스북이 리액트를 만들기 전에도 이미 수많은 프레임워크들이 존재했습니다. 페이스북에서는 이 프레임워크들에서 핵심적인 부분인 변화시켜준다는 것에 집중해서 어떤 DOM을 가져와서 뷰를 업데이트를 하는 것이 아니라 뷰를 날려버리고 새로 만들어 버리면 어떨까? 하는 발상에서 시작하였습니다.

그래서 Virtual DOM 이라는 가상의 DOM을 만들어 실제 브라우저의 DOM에 새로운걸 넣지 않고, 자바스크립트로 이루어진 가상 DOM에 한번 렌더링을 하고, 기존의 DOM과 비교를 한 다음에 정말 변화가 필요한 곳에만 업데이트를 해줍니다. Virtual DOM 을 사용함으로서, 데이터가 바뀌었을 때 어떻게 업데이트 할지를 고려하는게 아니라, 그냥 일단 바뀐 데이터로 그려놓고 비교를 한 다음에, 바뀐 부분만 찾아서 바꿔줍니다.

&nbsp;

### 리액트가 좋은 점

&nbsp;

리액트가 좋은 점으로 DOM으로 개발하는 것보다 빨라진다는 것을 생각하신다면 그건 잘못 된 것입니다. 실제로는 최적화작업을 손수한 DOM으로 개발하는 것이 더 빠를 경우가 많습니다. 그렇지만 그렇게 웹페이지의 기능을 개발하는 것 외에 DOM 관리하는 것에 많은 시간을 쏟아야 하고, 유지보수가 어려울 수 있습니다.
유지보수가 가능한 웹페이지를 만드는 것을 도와주는 것이 리액트가 좋은 점입니다.(충분히 빠르기도 합니다.)

리액트의 가장 좋은 점은 사용자가 많아서, 라이브러리들이 정말 많이 만들어집니다. 문제가 생겼을때 이미 해결한 다른 사람들의 의견을 들을 수 있기 때문에 빠르게 개발하기 좋습니다. jQuery, 혹은 일반 자바스크립트로 만들어진 라이브러리들도 리액트로 포팅되서 많이 작성되고 있습니다.



&nbsp;

참조. https://velopert.com/3612
