# Affiliate-API

NS홈쇼핑 입점을 위해 제공하는 Open API 입니다. 관련하여 추가 문의 내용은 itcs@nsmall.com 으로 문의하시면 보다 자세한 안내 드리겠습니다.

[Ver 1.29] (변경날짜 2017-11-29)

 네이버 가격비교에 제공하는 상품 필수정보 추가
 변경 사항
GD101:상품등록 
 -> 상품 상태 코드(GOODS_STAT_CD) 추가)
 -> 주문 제작 여부(ORDER_PRDT_YN) 추가)
 -> 국내 해외 방식 코드(DMST_OVS_MEANS_CD) 추가)
 -> 판매 방식 코드(SALE_MEANS_CD) 추가)
 -> 별도 설치비 여부(EXTRA_INSTF_YN) 추가)
 -> 차등 배송비 여부(DSCR_DLVRF_YN) 추가)
GD103:상품수정 
 -> 상품 상태 코드(GOODS_STAT_CD) 추가)
 -> 주문 제작 여부(ORDER_PRDT_YN) 추가)
 -> 국내 해외 방식 코드(DMST_OVS_MEANS_CD) 추가)
 -> 판매 방식 코드(SALE_MEANS_CD) 추가)
 -> 별도 설치비 여부(EXTRA_INSTF_YN) 추가)
 -> 차등 배송비 여부(DSCR_DLVRF_YN) 추가)

[Ver 1.28] (변경날짜 2017-11-08)

 상품 단품(옵션)의 대표상품.가격으로 선택 기능 추가
 변경 사항
GD101:상품등록 (대표 단품 순번(RPRSN_UNIT_SEQ) 추가)
GD103:상품수정 (대표 단품 코드(RPRSN_UNIT_CD) 추가)
CM103:상품별단품조회 (대표 가격 여부(RPRSN_YN) 추가)
[Ver 1.27] (변경날짜 2017-05-30)

 출고지정보API(GD112)에 필수항목 5개 자동승인 업체에 대한 필수 제외 기능
[Ver 1.26] (변경날짜 2017-05-26)

 출고지정보API()에 필수항목 5개 추가
 변경 사항
GD112:출고지정보 (배송수단 추가, 출고지 택배사, 반송택배사, AS출고지택배사, AS반송택배사 추가)
배송수단 상세 - (10: 택배직송, 20: 업체직송, 30: 자체, 40: 중량화물, 90: 배송없음)
[Ver 1.25] (변경날짜 2017-01-18)

업체 지연 사유 내용/미배송 출고 예정 일자 추가
[Ver 1.24] (변경날짜 2016-11-28)

안전 인증 코드/안전 인증 번호 추가
[Ver 1.23] (변경날짜 2016-02-17)

상품명 기술서 max 수정
