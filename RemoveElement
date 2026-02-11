import java.util.*;

public class RemoveElement {
    static int removeElement(int[] nums, int val) {
        int k = 0;
        for(int n : nums)
            if(n != val) nums[k++] = n;
        return k;
    }

    public static void main(String[] args) {
        int[] nums = {3,2,2,3};
        int k = removeElement(nums, 3);
        System.out.println(k);
        System.out.println(Arrays.toString(Arrays.copyOf(nums, k)));
    }
}
