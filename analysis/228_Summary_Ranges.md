Given a sorted integer array without duplicates, return the summary of its ranges.

For example, given [0,1,2,4,5,7], return ["0->2","4->5","7"].

### ����
���һ�������е�ranges
range�ĸ�������������, 1 2 3 4 5��range��1->5

### ���
����˳���жϹ�ȥ,�ж�a[i+1] - a[i]�Ƿ����1
��ȫ����O(n)�Ĳ���
