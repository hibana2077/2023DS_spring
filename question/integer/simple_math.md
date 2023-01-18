<!--
 * @Author: hibana2077 hibana2077@gmaill.com
 * @Date: 2023-01-18 16:01:59
 * @LastEditors: hibana2077 hibana2077@gmaill.com
 * @LastEditTime: 2023-01-18 16:11:36
 * @FilePath: /2023DS_spring/question/integer/simple_math.md
 * @Description: 这是默认设置,请设置`customMade`, 打开koroFileHeader查看配置 进行设置: https://github.com/OBKoro1/koro1FileHeader/wiki/%E9%85%8D%E7%BD%AE
-->
# Sample Math

## Question

有一天起床發現你轉生到了異世界，你的能力是「可編程式計算機」，但是在這個世界裡面，很多事情都要靠簡單的數學來解決，像是戰鬥、購買物品等等，為了讓你能夠在這個世界生存下去，你需要寫一個程式來幫你解決這些問題。

## Input

每一行代表一組測資，每一組測資包含一組數學運算式，並且保證運算式的結果不會超過 $2^{31}$ ， $a$ 和 $b$ 的範圍為 $-2^{31}$ 到 $2^{31}$ ， $ans$ $=$ $a$ $op$ $b$ ， $op$ 為 `+` 或 `*` 跟 `-` 。

## Output

對於每一組測資，請輸出運算式的結果。

## Sample Input

```text
1 + 1
2 * 3
```

## Sample Output

```text
2
6
```