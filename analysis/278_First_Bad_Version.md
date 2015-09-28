Suppose you have n versions [1, 2, ..., n] and you want to find out the first bad one, which causes all the following ones to be bad.

You are given an API bool isBadVersion(version) which will return whether version is bad. Implement a function to find the first bad version. You should minimize the number of calls to the API.

### ����
�ж���һ�������õ�һ�γ���BadVersion��λ��

�������ٵķ�������

### ���
��׼�Ķ��ֲ��ң��ҵ�һ��д��ʱ�򲻳����ϵ�д����
l = 1
r = n
while r > l:
    m = (l + r) / 2
    if isBadVersion(m):
        r = m - 1
    else:
        l = m + 1       