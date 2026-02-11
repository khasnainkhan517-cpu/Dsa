public class MaxConsecutiveOnes {
    static int findMaxConsecutiveOnes(int[] nums) {
        int max=0, count=0;
        for(int n: nums){
            if(n==1) max=Math.max(max, ++count);
            else count=0;
        }
        return max;
    }

    public static void main(String[] args) {
        System.out.println(findMaxConsecutiveOnes(new int[]{1,1,0,1,1,1}));
    }
}
