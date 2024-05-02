****선착순 100명에게 쿠폰이 지급되는 시스템****

[문제점]
![image](https://github.com/youngseonseo/CouponSystem/assets/70623206/747718b3-4b7f-4deb-99d6-e766c32b98f6)

1000명의 사용자가 쿠폰을 발급받기 위해 동시에 신청하는 것을 멀티 쓰레드로 구현 시,
위와 같이 100개의 쿠폰이 아닌 100개가 넘는 쿠폰이 발급되는 race Condition 발생
