package com.zwl.algorithms4.chapter1;

/**
 * @Description:
 * @Author: za-zhangwenlei
 * @Date: Created in 9:39 2021/9/26
 */
public class Gongyueshu {

    //最大公约数
    public static int gcd(int p, int q) {
        if (q == 0) return p;
        int r = p%q;
        return gcd(q, r);
    }

    public static void main(String[] args) {
        int p = 24, q = 48;
        // 第一步： p = 24, q = 48, r = 24;
        // 第二步： p = 48, q = 24, r = 0;
        // 第三步： p = 24, q = 0;
        System.out.println("最大公约数为：" + gcd(p, q));

        int m = 13, n = 12;
        // 第一步： p = 13, q = 12, r = 1;
        // 第二步： p = 12, q = 1, r = 0;
        // 第三步： p = 1, q = 0;
        System.out.println("最大公约数为：" + gcd(m, n));

        int i = 8, j = 12;
        // 第一步： p = 8, q = 12, r = 8;
        // 第二步： p = 12, q = 8, r = 4;
        // 第三步： p = 8, q = 4, r = 0;
        // 第四步： p = 4, q = 0;
        System.out.println("最大公约数为：" + gcd(i, j));
    }
}
