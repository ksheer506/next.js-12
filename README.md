**1. /infinite-scroll 구현 수정**  
무한 스크롤로 페이지를 구성하면 스크롤이 하단에 도달할 때 바로 다음 데이터를 받아오는 것이 일반적이지만, 푸터 영역이 계속 아래로 밀리게 되어 푸터 영역의 정보가 필요한 사용자는 끝없이 스크롤을 내릴 수밖에 없게 됩니다. 이러한 문제를 보완하기 위해 "더보기" 버튼을 배치해 "더보기" 버튼을 누른 후에야 무한 스크롤이 작동하도록 했습니다.

**2. ProductList, ProductItem 로딩 중 Skeleton 표시**  
ProductList, ProductItem의 이미지가 모두 불러와질 때까지 Skeleton을 표시하도록 해 사용자 경험을 향상 했습니다.
