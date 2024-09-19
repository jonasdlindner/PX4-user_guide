# 기체 선택

PX4는 항공, 지상, 수상 및 수중 차량을 지원합니다. PX4와 호환되는 차량 프레임의 전체 목록은 [기체 정의서](../airframes/airframe_reference.md)에서 확인할 수 있습니다.

목적에 적합한 기체를 선택하십시오.

- **멀티 콥터**는 일반적으로 저속 단거리 비행용이며 정밀한 호버링과 수직 이착륙이 장점입니다. PX4에는 간편 비행 모드를 제공하며, 가장 인기있는 비행체입니다.
- **고정익**은 장거리 고속 비행용으로 항공감시 등에 적합합니다. 멀티콥터보다 이착륙이 어렵고 호버링이나 저속 비행(예 : 수직 구조물 조사 등)에는 적합하지 않습니다.
- **VTOL**(수직 이착륙기)은 틸트로터, 테일 시터, 쿼드 플레인 등의 다양한 유형이 있습니다. 멀티콥터의 수직 이착륙, 호버링의 장점과 고정익의 전방 비행의 장점을 가지고 있습니다. 멀티 콥터와 고정익 항공기보다 더 비싸고 제작과 조정이 더 어렵습니다.
- **비행선/풍선**은 일반적으로 비행 속도와 방향을 제한적으로 (또는 전혀 제어하지 않는) 비용으로 고고도의 장기 비행을 위한 공기보다 가벼운 기체입니다.
- **로버**는 자동차와 같은 지상용 차량입니다. 제어가 용이하고, 사용하기 편리합니다.
- **보트**는 수상 차량입니다.
- **잠수정**은 수중 차량입니다.

:::note PX4의 초기 [기체 설정](../config/airframe.md)은 *QGroundControl*을 사용합니다.

![프레임 선택 ](../../assets/qgc/setup/airframe/airframe_px4.jpg)
:::