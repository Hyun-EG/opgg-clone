# OP.GG 클론

[원본 사이트](https://www.op.gg/) <br/>
[클론 사이트](https://animated-llama-195ed0.netlify.app/)

## 주요사항

![header](https://github.com/KDT1-FE/KDT8-M1/assets/106307387/61cf2d7c-9a39-418b-9bec-c673a7cbb213)

```html
header
라인을 클래스 firstLine,rightMenu,secondLine, thirdLine 나누었습니다.
firstLine 좌측패딩을 로고 width만큼 주고 로고를 넣었습니다. 백그라운드 컬러를
검정계열로 주고, li:first-child를 사용하여 배경컬러를 넣었으며 nav ul li태그를
사용하여 정리하였습니다. hover를 줘서 포인터 효과를 주었습니다. secondLine
아이템들에 좌측마진을 주고 first-child 사용하여 첫아이템만 좌측마진을 0을 주고
정렬하였습니다. hover효과를 주고 home에만 border를 없앴습니다. thirdLine 배경을
넣고 hover를 사용하였습니다.
```

![main](https://github.com/KDT1-FE/KDT8-M1/assets/106307387/1a37b815-364e-4484-bb8d-bf1d8c51b1a9)

```html
검색창 위에있는 이미지는 스몰더라는 신규챔피온입니다.
클래스명 또한 스몰더로 지정하였고, width값을 주고 마진을 0 auto를 줘서 정렬하였습니다.
클래스명 middle에서는 flex-direction을 컬럼으로 줘서 아래방향으로 정렬하였습니다.
searchBox 박스쉐도우를 주고, radius를 사용하여 박스를 꼭지점을 깎아줬습니다.
text-align을 left 줘서 검색과 지역을 좌측정렬하였습니다.
searchWrapper에는 flex:1을 줬습니다. input을 클릭했을때 검정테두리가 생겨서
outline:none을 줘서 제거하였습니다. 밑에 배너는 middleSecondBanner , middleThirdBanner라고
클래스명을 만들었고, 광고부분이라서 이미지 삽입을 하였습니다. 광고밑에는 섹션을
두개 만들었습니다. 기존사이트에는 그리드가 포함 돼있지 않아서, 좌측은 플렉스,
우측은 그리드를 조금씩 응용하여 바꿔봤습니다.
```

![footer](https://github.com/KDT1-FE/KDT8-M1/assets/106307387/fafc0222-faa8-4c44-869f-73553d68ad5c)

```html
footer
로고를 좌측에 넣고 상단에 OP.GG Products Apps Resources More는 같은 클래스로 묶어서 바꿔줬습니다.
flex를 활용하여 정렬하고 각 a태그로 만들어줬습니다.
products와 apps에 글 우측 게임기모양은 이미지를 본사이트에서 이미지를 불러왔습니다.
footerBottom 부분은 먼저 border탑을 사용하여 선을 그어주었고,
flex를 활용하여 정렬하였습니다. ul li태그를 사용하여 정리하였고
제일하단에 카피라이터 영어문단은 p태크를 사용하였습니다.
sns는 본사이트에서 이미지를 가져와 a태그안에 감싸서 넣어줬습니다.
```

## 오픈 그래프

```html
<meta property="og:type" content="website" />
<meta property="og:site_name" content="OPGG" />
<meta
  property="og:title"
  content="롤 전적 검색은 OP.GG - 챔피언 공략과 게임 전적, 라이엇 아이디 태그 검색"
/>
<meta
  property="og:description"
  content="챔피언 공략과 게임 전적, 라이엇 아이디 태그 검색"
/>
<meta
  property="og:image"
  content="https://s-lol-web.op.gg/images/icon/opgglogo.svg?v=1707283412529"
/>
<meta property="og:url" content="https://www.op.gg/" />
```

## 트위터 카드

```html
<meta property="twitter:card" content="summary" />
<meta property="twitter:site" content="OPGG" />
<meta
  property="twitter:title"
  content="롤 전적 검색은 OP.GG - 챔피언 공략과 게임 전적, 라이엇 아이디 태그 검색"
/>
<meta
  property="twitter:description"
  content="챔피언 공략과 게임 전적, 라이엇 아이디 태그 검색"
/>
<meta
  property="twitter:image"
  content="https://s-lol-web.op.gg/images/icon/opgglogo.svg?v=1707283412529"
/>
<meta property="twitter:url" content="https://www.op.gg/" />
```


## Favicon

```html
<img
  src="https://s-lol-web.op.gg/images/icon/opgglogo.svg?v=1707283412529"
  width="65"
  height="16"
  alt="OP.GG"
/>
```

## Header
```html

<header>
    <div class="headerMenu">
      <div class="firstLine">
        <a class="logo" href="javascript:void(0)">
          <img src="https://s-lol-web.op.gg/images/icon/opgglogo.svg?v=1707283412529" width="65" height="16"
            alt="OP.GG">
        </a>
        <nav>
          <ul>
            <li>
              <span>
                <img
                  src="https://opgg-gnb.akamaized.net/static/images/icons/lol.svg?image=q_auto,f_webp,w_48,h_48&amp;v=1707283412529"
                  width="24" height="24" alt="리그오브레전드">
                <span>리그오브레전드</span>
              </span>
            </li>
            <li>
              <a href="javascript:void(0)" rel="noreferrer"><img
                  src="https://opgg-gnb.akamaized.net/static/images/icons/pal.svg?image=q_auto,f_webp,w_48,h_48&amp;v=1707283412529"
                  width="24" height="24" alt="팰월드">
                <span class="palWorld">B</span>
                <span>팰월드</span>
              </a>
            </li>
            <li>
              <a href="javascript:void(0)">
                <img
                  src="https://opgg-gnb.akamaized.net/static/images/icons/dskapp.svg?image=q_auto,f_webp,w_48,h_48&amp;v=1707283412529"
                  width="24" height="24" alt="데스크톱">
                <span>데스크톱</span>
              </a>
            </li>
            <li>
              <a href="javascript:void(0)">
                <img
                  src="https://opgg-gnb.akamaized.net/static/images/icons/tft.svg?image=q_auto,f_webp,w_48,h_48&amp;v=1707283412529"
                  width="24" height="24" alt="전략적 팀 전투">
                <span>전략적 팀 전투</span>
              </a>
            </li>
            <li>
              <a href="javascript:void(0)">
                <img
                  src="https://opgg-gnb.akamaized.net/static/images/icons/val.svg?image=q_auto,f_webp,w_48,h_48&amp;v=1707283412529"
                  width="24" height="24" alt="발로란트">
                <span>발로란트</span>
              </a>
            </li>
            <li>
              <a href="javascript:void(0)"><img
                  src="https://opgg-gnb.akamaized.net/static/images/icons/pubg.svg?image=q_auto,f_webp,w_48,h_48&amp;v=1707283412529"
                  width="24" height="24" alt="배틀그라운드">
                <span>배틀그라운드</span>
              </a>
            </li>
            <li><a href="javascript:void(0)">
                <img
                  src="https://opgg-gnb.akamaized.net/static/images/icons/overwatch.svg?image=q_auto,f_webp,w_48,h_48&amp;v=1707283412529"
                  width="24" height="24" alt="오버워치2">
                <span>오버워치2</span>
              </a>
            </li>
            <li><a href="javascript:void(0)">
                <img
                  src="https://opgg-gnb.akamaized.net/static/images/icons/esports.svg?image=q_auto,f_webp,w_48,h_48&amp;v=1707283412529"
                  width="24" height="24" alt="이스포츠">
                <span>이스포츠</span>
              </a>
            </li>
            <li>
              <a href="javascript:void(0)">
                <img
                  src="https://opgg-gnb.akamaized.net/static/images/icons/talk.svg?image=q_auto,f_webp,w_48,h_48&amp;v=1707283412529"
                  width="24" height="24" alt="톡피지지">
                <span>톡피지지</span>
              </a>
            </li>
            <li><a href="javascript:void(0)">
                <img
                  src="https://opgg-gnb.akamaized.net/static/images/icons/gigs.svg?image=q_auto,f_webp,w_48,h_48&amp;v=1707283412529"
                  width="24" height="24" alt="Gigs">
                <span class="palWorld">N</span>
                <span>Gigs</span>
              </a>
            </li>
            <li>
              <a href="javascript:void(0)">
                <img
                  src="https://opgg-gnb.akamaized.net/static/images/icons/duo.svg?image=q_auto,f_webp,w_48,h_48&amp;v=1707283412529"
                  width="24" height="24" alt="Duo">
                <span>Duo</span>
              </a>
            </li>
          </ul>
        </nav>
        <div class="rightMenu">
          <button class="ghost">
            <span class="hidden">1:1 문의하기</span>
          </button>
          <button class="brightNess">
            <span class="hidden">Theme Button</span>
          </button>
          <button class="language">
            <span class="hidden">언어</span>
          </button>
        </div>
        <div class="loginMenu">
          <button class="login">
            <a href="javascript:void(0)">로그인</a>
          </button>
        </div>
      </div>
      <div class="secondLine">
        <div class="routeMenu">
          <nav class="routeNav">
            <ul class="routeList">
              <li class="routeItem">
                <a href="javascript:void(0)">
                  <div class="home">홈</div>
                </a>
              </li>
              <li class="routeItem">
                <a href="javascript:void(0)">
                  <div class="champion">챔피언 분석</div>
                </a>
              </li>
              <li class="routeItem">
                <a href="javascript:void(0)">
                  <div class="gameMode">게임 모드</div>
                </a>
              </li>
              <li class="routeItem">
                <a href="javascript:void(0)">
                  <div class="urf">우르프
                    <div class="urfTag">N</div>
                  </div>
                </a>
              </li>
              <li class="routeItem">
                <a href="javascript:void(0)">
                  <div class="statistics">통계</div>
                </a>
              </li>
              <li class="routeItem">
                <a href="javascript:void(0)">
                  <div class="lanking">랭킹</div>
                </a>
              </li>
              <li class="routeItem">
                <a href="javascript:void(0)">
                  <div class="pro">프로관전</div>
                </a>
              </li>
              <li class="routeItem">
                <a href="javascript:void(0)">
                  <div class="multiSearch">멀티서치</div>
                </a>
              </li>
              <li class="routeItem">
                <a href="javascript:void(0)">
                  <div class="talk">커뮤니티</div>
                </a>
              </li>
              <li class="routeItem">
                <a href="javascript:void(0)">
                  <div class="edu">강의</div>
                </a>
              </li>
              <li class="routeItem">
                <a href="javascript:void(0)">
                  <div class="myPage">마이페이지</div>
                </a>
              </li>
            </ul>
          </nav>
        </div>
      </div>
      <div class="banner">
        <div class="thirdLine">
          <a href="javascript:void(0)">배치고사 연승으로 협곡을 지배하세요! 🚀</a>
        </div>
      </div>
  </header>
````
      
## Main

```html
<main>
  <h1 class="hidden">OP.GG</h1>
  <div class="smallder">
    <img
      src="https://meta-static.op.gg/logo/image/8a600438ab0430d4094b6d4e6ecb3d84.png?image=q_auto,f_webp,w_auto,h_448&amp;v=1707283412529"
      height="224"
      alt="OP.GG logo (스몰더)"
      title="스몰더"
    />
  </div>
  <div class="middle">
    <div>
      <form class="searchBox">
        <div>
          <small class="label">지역</small>
          <div class="pickArea">
            <label class="hidden" for="kr">kr</label>
            <select id="kr">
              <option value="kr">KR</option>
              <option value="na">NA</option>
              <option value="euw">EUW</option>
              <option value="oce">OCE</option>
              <option value="kr" selected="">KR</option>
              <option value="jp">JP</option>
            </select>
          </div>
          <div class="pickKr">
            <div>
              <button type="button" class="korea">
                <span>Korea</span>
              </button>
            </div>
          </div>
        </div>
        <div class="searchWrapper">
          <label for="searchHome" class="label">검색</label>
          <input
            id="searchHome"
            name="search"
            autocomplete="off"
            type="text"
            value
          />
          <label for="searchHome" class="searchPlaceholder">
            <span class="placeHolderHome"> 플레이어 이름 + </span>
            <span class="placeHoderTag"> #KR1 </span>
          </label>
        </div>
        <button class="gg-btn" type="submit">.GG</button>
      </form>
    </div>
    <div class="middleSecond">
      <div class="middleSecondBanner"></div>
    </div>
  </div>
  <div class="middleThird">
    <div class="middleThirdBanner">
      <span
        ><img
          src="https://search.pstatic.net/common/?src=http%3A%2F%2Fblogfiles.naver.net%2FMjAyNDAxMThfMTE0%2FMDAxNzA1NTU1MzIwMzQx.t4Vg3vuXLJHzSYGfYRjS8mupii4__BtXrKXqbjvcr-Ug.kIecAmp7KT6Noyvas69z_jUp6o3EEMjmF33KVuL5sPIg.JPEG.marugameacademy%2F%25BF%25F8%25B5%25F4_%25B4%25EB%25C7%25A5_%25C3%25A8%25C7%25C7%25BE%25F0.jpg&type=sc960_832"
          alt="롤"
      /></span>
    </div>
  </div>
  <div class="middleTable">
    <section class="opggTalk">
      <h2><a href="javascript:void(0)">OP.GG Talk 인기글</a></h2>
      <div>
        <span class="numbering">1</span>
        <img
          src="https://images.velog.io/images/kyungjin/post/fdd5cc22-dfdc-4091-a2fb-039ce36ce9d8/%ED%8B%B0%EB%AA%A8.png"
          alt="티모"
          width="90px"
          height="70px"
        />
        <span class="topic"><a href="">프론트엔드는 패스트캠퍼스</a></span>
        <span class="saw">[12]</span>
      </div>
      <div>
        <span class="numbering">2</span>
        <img
          src="https://cdn-store.leagueoflegends.co.kr/images/v2/emotes/3202.png"
          alt="이즈"
          width="90px"
          height="70px"
        />
        <span class="topic"><a href="">백엔드는 패스트캠퍼스</a></span>
        <span class="saw">[24]</span>
      </div>
      <div>
        <span class="numbering">3</span>
        <img
          src="https://cdn-store.leagueoflegends.co.kr/images/v2/emotes/4477.png"
          alt="용"
          width="90px"
          height="70px"
        />
        <span class="topic"><a href="">그로스 마케팅은 패스트캠퍼스</a></span>
        <span class="saw">[52]</span>
      </div>
      <div>
        <span class="numbering">4</span>
        <img
          src="https://cdn-store.leagueoflegends.co.kr/images/v2/emotes/4033.png"
          alt="콘"
          width="90px"
          height="70px"
        />
        <span class="topic"><a href="">프로덕트 매니저는 패스트캠퍼스</a></span>
        <span class="saw">[11]</span>
      </div>
      <div>
        <span class="numbering">5</span>
        <img
          src="https://cdn-store.leagueoflegends.co.kr/images/v2/emotes/4035.png"
          alt="크산테"
          width="90px"
          height="70px"
        />
        <span class="topic"><a href="">UXUI 디자인은 패스트캠퍼스</a></span>
        <span class="saw">[36]</span>
      </div>
    </section>
    <section class="playerTab">
      <div>
        <span>
          <img
            src="https://images.contentstack.io/v3/assets/blt731acb42bb3d1659/blte41a162aed9339b7/5db05fc60b39e86c2f83dc0d/RiotX_ChampionList_garen.jpg?quality=90&width=250"
            alt="가렌"
            width="177px"
            height="256px"
          />
        </span>
        <span>
          <img
            src="https://images.contentstack.io/v3/assets/blt731acb42bb3d1659/bltb94b4161d8022c45/5db05fdfe9d7526ab429e53c/RiotX_ChampionList_lux.jpg?quality=90&width=250"
            alt="럭스"
            width="177px"
            height="256px"
          />
        </span>
        <span>
          <img
            src="https://images.contentstack.io/v3/assets/blt731acb42bb3d1659/blt075d278529811445/5db05fde6af83b6d7032c8fe/RiotX_ChampionList_leesin.jpg?quality=90&width=250"
            alt="리신"
            width="177px"
            height="256px"
          />
        </span>
        <span>
          <img
            src="https://images.contentstack.io/v3/assets/blt731acb42bb3d1659/bltc81eece55f126d2d/5db05fe86af83b6d7032c904/RiotX_ChampionList_morgana.jpg?quality=90&width=250"
            alt="모르가나"
            width="177px"
            height="256px"
          />
        </span>
        <span>
          <img
            src="https://images.contentstack.io/v3/assets/blt731acb42bb3d1659/blt825d0c333f6e74ae/5db060142140ec675d68f4bb/RiotX_ChampionList_velkoz.jpg?quality=90&width=250"
            alt="벨코즈"
            width="177px"
            height="256px"
          />
        </span>
        <span>
          <img
            src="https://images.contentstack.io/v3/assets/blt731acb42bb3d1659/bltc8ca2e9bba653dda/5db05fb2dc674266df3d5d30/RiotX_ChampionList_brand.jpg?quality=90&width=250"
            alt="브랜드"
            width="177px"
            height="256px"
          />
        </span>
      </div>
      <span class="playerTabEnd">
        <span class="white">Grid</span>
        <span class="black">X</span>
        <span class="orange">League of Legend</span>
      </span>
    </section>
  </div>
</main>
```

## Footer

```html
<footer>
  <div>
    <section style="display: flex;">
      <div class="footerLogo">
        <a href="javascript:void(0)">
          <img
            src="https://s-lol-web.op.gg/images/icon/icon-opgglogo-white.svg?v=1708507553015"
            width="99"
            height="24"
            alt="OP.GG"
            loading="lazy"
          />
        </a>
      </div>
      <div>
        <a class="aTitle" href="javascript:void(0)">OP.GG</a>
        <a href="javascript:void(0)">About OP.GG</a>
        <a href="javascript:void(0)">Company</a>
        <a href="javascript:void(0)">Blog</a>
        <a href="javascript:void(0)">로고 히스토리</a>
      </div>
      <div>
        <a class="aTitle" href="javascript:void(0)">Products</a>
        <a href="javascript:void(0)"
          >리그오브레전드
          <img
            src="https://s-lol-web.op.gg/images/icon/icon-game-white.svg?v=1708507553015"
            width="16"
            height="16"
            alt="리그오브레전드"
            class="game"
          />
        </a>
        <a href="javascript:void(0)"
          >팰월드
          <img
            src="https://s-lol-web.op.gg/images/icon/icon-game-white.svg?v=1708507553015"
            width="16"
            height="16"
            alt="팰월드"
            class="game"
        /></a>
        <a href="javascript:void(0)"
          >데스크톱
          <img
            src="https://s-lol-web.op.gg/images/icon/icon-game-white.svg?v=1708507553015"
            width="16"
            height="16"
            alt="데스크톱"
            class="game"
          />
        </a>
        <a href="javascript:void(0)"
          >전략적 팀 전투
          <img
            src="https://s-lol-web.op.gg/images/icon/icon-game-white.svg?v=1708507553015"
            width="16"
            height="16"
            alt="전략적 팀 전투"
            class="game"
          />
        </a>
        <a href="javascript:void(0)"
          >발로란트
          <img
            src="https://s-lol-web.op.gg/images/icon/icon-game-white.svg?v=1708507553015"
            width="16"
            height="16"
            alt="발로란트"
            class="game"
          />
        </a>
        <a href="javascript:void(0)"
          >배틀그라운드
          <img
            src="https://s-lol-web.op.gg/images/icon/icon-game-white.svg?v=1708507553015"
            width="16"
            height="16"
            alt="배틀그라운드"
            class="game"
          />
        </a>
        <a href="javascript:void(0)"
          >오버워치2
          <img
            src="https://s-lol-web.op.gg/images/icon/icon-game-white.svg?v=1708507553015"
            width="16"
            height="16"
            alt="오버워치2"
            class="game"
          />
        </a>
        <a href="javascript:void(0)"
          >이스포츠
          <img
            src="https://s-lol-web.op.gg/images/icon/icon-game-white.svg?v=1708507553015"
            width="16"
            height="16"
            alt="이스포츠"
            class="game"
          />
        </a>
        <a href="javascript:void(0)"
          >톡피지지
          <img
            src="https://s-lol-web.op.gg/images/icon/icon-game-white.svg?v=1708507553015"
            width="16"
            height="16"
            alt="톡피지지"
            class="game"
          />
        </a>
        <a href="javascript:void(0)"
          >Gigs
          <img
            src="https://s-lol-web.op.gg/images/icon/icon-game-white.svg?v=1708507553015"
            width="16"
            height="16"
            alt="Gigs"
            class="game"
          />
        </a>
        <a href="javascript:void(0)"
          >Duo
          <img
            src="https://s-lol-web.op.gg/images/icon/icon-game-white.svg?v=1708507553015"
            width="16"
            height="16"
            alt="Duo"
            class="game"
          />
        </a>
      </div>
      <div>
        <a class="aTitle" href="javascript:void(0)">Apps </a>
        <a href="javascript:void(0)"
          >OP.GG Android App
          <img
            src="https://s-lol-web.op.gg/images/icon/icon-game-white.svg?v=1708507553015"
            width="16"
            height="16"
            alt="OP.GG Android App"
            class="game"
          />
        </a>
        <a href="javascript:void(0)"
          >OP.GG iOS App
          <img
            src="https://s-lol-web.op.gg/images/icon/icon-game-white.svg?v=1708507553015"
            width="16"
            height="16"
            alt="OP.GG iOS App"
            class="game"
          />
        </a>
        <a href="javascript:void(0)"
          >TFT Android App
          <img
            src="https://s-lol-web.op.gg/images/icon/icon-game-white.svg?v=1708507553015"
            width="16"
            height="16"
            alt="TFT Android App"
            class="game"
          />
        </a>
        <a href="javascript:void(0)"
          >TFT iOS App
          <img
            src="https://s-lol-web.op.gg/images/icon/icon-game-white.svg?v=1708507553015"
            width="16"
            height="16"
            alt="Apps"
            class="game"
          />
        </a>
        <a href="javascript:void(0)">TalkG Android App</a>
        <a href="javascript:void(0)">TalkG iOS App</a>
      </div>
      <div>
        <a class="aTitle" href="javascript:void(0)">Resources</a>
        <a href="javascript:void(0)">개인정보처리방침</a>
        <a href="javascript:void(0)">이용약관</a>
        <a href="javascript:void(0)">도움말</a>
        <a href="javascript:void(0)">이메일 문의하기</a>
        <a href="javascript:void(0)">고객센터 문의</a>
      </div>
      <div>
        <a class="aTitle" href="javascript:void(0)">More</a>
        <a href="javascript:void(0)">제휴</a>
        <a href="javascript:void(0)">광고</a>
        <a href="javascript:void(0)">채용</a>
      </div>
    </section>
    <section class="footerBottom">
      <div class="footerBottonFirst">
        <ul class="company">
          <li>
            <span>주식회사 오피지지 (OP.GG)</span>
          </li>
          <li>
            <span>통신판매업신고 :</span>
            <span>제2019-서울강남-01973호</span>
          </li>
          <li>
            <span>사업자등록번호 :</span>
            <span>295-88-00023</span>
          </li>
          <li>
            <span>대표자 :</span>
            <span>최상락</span>
          </li>
          <li>
            <span
              >서울특별시 강남구 테헤란로 507, 1층, 2층(삼성동,
              wework빌딩)</span
            >
          </li>
          <li>
            <span>전화 :</span>
            <span>02-455-9903 (평일 09:00 ~ 18:00)</span>
          </li>
          <li>
            <span>이메일 :</span>
            <span>
              <a href="javascript:void(0)">service@op.gg</a>
            </span>
          </li>
        </ul>
        <p class="copyright">
          © 2012- 2024 OP.GG. OP.GG is not endorsed by Riot Games and does not
          reflect the views or opinions of Riot Games or anyone officially
          involved in producing or managing League of Legends. League of Legends
          and Riot Games are trademarks or registered trademarks of Riot Games,
          Inc. League of Legends © Riot Games, Inc.
        </p>
      </div>
      <nav class="sns">
        <a href="javascript:void(0)">
          <img
            src="https://s-lol-web.op.gg/images/icon/icon-logo-instagram.svg?v=1708507553015"
            width="24"
            height="24"
            alt="instagram account"
            loading="lazy"
          />
        </a>
        <a>
          <img
            src="https://s-lol-web.op.gg/images/icon/icon-logo-youtube.svg?v=1708507553015"
            width="24"
            height="24"
            alt="twitter account"
            loading="lazy"
          />
        </a>
        <a>
          <img
            src="https://s-lol-web.op.gg/images/icon/icon-logo-x.svg?v=1708507553015"
            width="24"
            height="24"
            alt="twitter account"
            loading="lazy"
          />
        </a>
        <a>
          <img
            src="https://s-lol-web.op.gg/images/icon/icon-logo-facebook.svg?v=1708507553015"
            width="24"
            height="24"
            alt="facebook account"
            loading="lazy"
          />
        </a>
      </nav>
    </section>
  </div>
</footer>
```
