Divide two integers without using multiplication, division and mod operator.

If it is overflow, return MAX_INT.

### ����
�����óˡ�����Mod����������������������
Ҫ��������MAX_INT��ʱ�����MAX_INT

### �ⷨ
Ψһ��Ҫ���е��� MIN_INT �� MAX_INT �� 1
���� MIN_INT / 1 �������������������

����ʹ�����ƶ��ֲ��ҵķ���

  while dividend >= divisor:
            x = divisor
            i = 1
            while dividend >= x + x:
                x += x
                i += i
            dividend -= x
            ans += i