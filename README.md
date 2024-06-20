# android-shopping

## 쇼핑 장바구니

### 1단계 - 상품 목록
**기능 명세**
- 상품 목록 화면 (ProductListActivity)
  - [ ] 툴바의 장바구니 아이콘을 클릭하면 장바구니로 이동한다.
  - [ ] 상품을 클릭하면 상품 상세로 이동한다.

- 상품 상세 화면 (ProductDetailActivity)
  - [ ] 상품을 클릭하면 상품 상세로 이동한다.
  - [ ] 상품 상세에서 장바구니에 상품을 담을 수 있다.
  - [ ] x 아이콘을 누르면 상품 목록으로 이동한다.

- 장바구니 화면 (CartActivity)
  - [ ] 장바구니에서 원하는 상품을 삭제할 수 있다.

**프로그래밍 요구 사항**
* 상품 목록은 RecyclerView에 GridLayoutManager를 설정하여 구현한다.
* ListAdapter, DiffUtil을 사용하지 않는다.
* 이미지 로딩을 위해 Glide를 사용한다.
* 데이터가 어떻게 저장되는지는 고민하지 않아도 된다.
