# labreport 3
## Part 1: bug
1. failed-inducing <br>
 `int[] input1 = new int[]{1, 2, 3}` would lead to a failure, the specific code for JUnit test is shown below <br>
 ```
  @Test
  public void testReversed1() {
    int[] input1 = {1, 2, 3};
    assertArrayEquals(new int[]{3, 2, 1}, ArrayExamples.reversed(input1));
  }
```
<br>
2. An input that doesn't induce a failure<br>
`int[] input1 = { }` would not lead to a failure, the specific code for JUnit test is shown below<br>
```
@Test
  public void testReversed() {
    int[] input1 = { };
    assertArrayEquals(new int[]{ }, ArrayExamples.reversed(input1));
  }
```
<br>
3. 

   
