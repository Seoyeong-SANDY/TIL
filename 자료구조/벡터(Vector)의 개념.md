벡터는 순서대로 데이터를 저장하는 도구이다. 리스트와 다르게 메모리에서 연속된 공간을 가진다. 
기존 배열보다 크기를 동적으로 늘릴 수 있는 장점이 있다.
중간에 삽입이 가능하다. 하지만 O(n)이 걸린다. 삽입하는 위치 뒤 공간에서 끝까지 한 칸씩 뒤로 밀어야 하기 때문이다.
사이즈가 부족할 때 벡터가 할당가능한 메모리를 늘리는 것이다.
일정한 크기로 늘리지 말고 기존 벡터의 두 배 크기로 늘리는 것이다. 