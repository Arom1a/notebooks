Seeing `.length` means you know that's constant, and where you see `.size()` it isn't.

`.size()` is for `ArrayList` and `List`.
`.length` is for `Array`.
`.length()` is for `String`.

```java
import java.util.ArrayList;
import java.util.Arrays;
import java.util.List;

public class Test {
    public static void main(String[] args) {
        ArrayList<Integer> numArrayList = new ArrayList<Integer>(Arrays.asList(1, 2, 3, 4, 5));
        System.out.println(numArrayList.size());

        List<Integer> numList = Arrays.asList(1, 2, 3, 4, 5);
        System.out.println(numList.size());

        int[] numArray = { 1, 2, 3, 4, 5 };
        System.out.println(numArray.length);

        String numString = "12345";
        System.out.println(numString.length());
    }
}
```
