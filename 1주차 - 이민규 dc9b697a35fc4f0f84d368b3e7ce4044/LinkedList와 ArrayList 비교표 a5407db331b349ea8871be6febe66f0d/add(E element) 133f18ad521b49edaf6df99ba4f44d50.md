# add(E element)

ArrayList: O(1) amortized (배열의 re-sizing을 N에 비례해서 늘릴 경우 일반적으로 2N으로 re-sizing). worst-case O(N) (배열이 꽉차서 새로 생성 후 원소를 복사해야 하는 경우)
LinkedList: O(1). add(int index, E element) 에서 index == list.size()인 special case