#### 침투적 기술과 비침투적 기술
침투적invasive 기술은 기술을 적용했을 때 애플리케이션 코드에 기술 관련 API가 등장하거나, 특정 인터페이스나 클래스를 사용하도록 강제하는 기술
> 따라서 침투적 기술을 사용하면 애플리케이션 코드가 해당 기술에 종속된다.

비 침투적noninvasive 기술은 애플리케이션 로직을 담은 코드에 아무런 영향을 주지 않고 적용이 가능하다.
> 따라서 기술에 종속적이지 않은 순수한 코드를 유지할 수 있게 해준다.

**스프링은 비침투적인 기술의 대표적인 예** 다. 그래서 스프링 컨테이너 없는 DI 테스트도 가능한 것이다.

#### 동등 분할 equivalent partitioning
같은 결과를 내는 값의 범위를 구분해서 각 대표값으로 테스트를 하는 방법