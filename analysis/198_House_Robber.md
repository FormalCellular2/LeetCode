You are a professional robber planning to rob houses along a street. Each house has a certain amount of money stashed, the only constraint stopping you from robbing each of them is that adjacent houses have security system connected and it will automatically contact the police if two adjacent houses were broken into on the same night.

Given a list of non-negative integers representing the amount of money of each house, determine the maximum amount of money you can rob tonight without alerting the police.

### ����
һ��С͵Ҫ͵Ǯ����һ�����飬��ʾһ�ŷ�����ӵ�е�Ǯ��������������͵�������������ӡ�
���ܹ���õ�Ǯ����������Ƕ��١�

### ���
��׼�Ķ�̬�滮���⡣

���쵽��ǰ�ڵ�i��������֪ǰi-1���ڵ�����Ž⡣
��ô�ڵ�i�����Ž�Ϊ  ���ڵ�i-2�����Ž� �� �ڵ�i��Ǯ�� �� ���ڵ�i-1�����Ž⣩ ���еĴ��ߡ�

����0�ڵ�����Ž�Ϊnums[0]

�� dp[i] = max(dp[i - 1],dp[i - 2] + nums[i])