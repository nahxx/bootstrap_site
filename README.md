# bootstrap_site
<h4>부트스트랩을 사용하여 사이트 구현하기</h4>
<ol>
  <li>22/05/24 => 사이트 선택 후 부트스트랩을 이용하여 콘텐츠 배치 </li>
</ol><br>
<h4>작업 중 느낀점</h4>
<ul>
  <li>22/05/24 메인화면 콘텐츠 배치
    <ol>
      <li>처음 부트스트랩의 다양한 예시 중에서 원하는 것을 골라 복사 후 수정할 때 각 박스의 역할과 클래스명의 역할을 제대로 이해하지 못해 애를 먹었다. 그래도 최대한 다양한 예시를 참고하여 구현하려고 노력했다.</li>
      <li>각 요소를 커스텀할 때 너비나 폰트 사이즈등의 경우 클래스명으로 이미 지정이 되어 있어서 css로 수정할 경우 적용되지 않았다. 구글링을 통해 각 클래스명의 의미와 내가 원하는 css를 적용하기 위해 필요한 클래스명을 찾아 적용했다.</li>
      <li>메인페이지를 원 사이트처럼 커스텀후 미디어쿼리를 적용을 위해 col-sm 클래스명을 추가했다. col 6개를 3개씩 row 2개로 감쌌던 shop 섹션에 col-sm-6을 적용하니 3/3 나누어서 배치가 되었다. 2개씩 짝지어서 나타나게 하기 위해 row를 하나로 col 6개를 감쌌다.</li>
      <li>shop 섹션에서 bedge를 가운데정렬로 적용하고 싶었는데 방법을 찾지못했다.</li>
      <li>brand 섹션의 이미지가 화면 너비가 줄었을 때 영역을 벗어나는 오류 수정 필요</li>
      <li>메인배너의 이미지가 화면 너비가 줄었을 때 잘리는 오류 수정 필요</li>
    </ol>
  </li>
  <li>22/05/25 메인화면 커스텀 수정, 서브페이지 구현
    <ol>
      <li>매인배너의 이미지와  brand의 이미지에 img-fluid 클래스를 추가해주니 사이트 너비에 따라 크기가 조정되었다.</li>
      <li>사이트 너비 변경에 따른 배치가 좀더 자연스럽게 하기 위해 col-lg 클래스를 추가해주고 col-md 클래스를 수정했다.</li>
      <li>서브페이지 skin.html의 전체 레이아웃을 앨범을 이용하여 구현했다. 맨 아래의 페이지는 pagination을 가져와서 커스텀했다.</li>
      <li>메뉴영역에 카트아이콘 추가 밑 배치를 수정했다.</li>
    </ol>
  </li>
  <li>22/05/26 메인페이지 css 수정
    <ol>
      <li>매인배너 및 메뉴 css 수정</li>
    </ol>
  </li>
</ul>
