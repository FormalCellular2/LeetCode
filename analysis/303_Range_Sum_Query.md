Given nums = [-2, 0, 3, -5, 2, -1]

sumRange(0, 2) -> 1
sumRange(2, 5) -> -1
sumRange(0, 5) -> -3
Note:
You may assume that the array does not change.
There are many calls to sumRange function.

### ����
�����������Ӷκ�

### ���
O(n)��ʱ������ sum[j],j form 1 to n �Ľ��.�ֶκ�i��j���� sum[j] - sum[i]