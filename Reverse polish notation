import java.util.*;

public class EvaluateReversePolishNotation {
    static int evalRPN(String[] tokens) {
        Stack<Integer> st=new Stack<>();
        for(String t:tokens){
            if("+-*/".contains(t)){
                int b=st.pop(), a=st.pop();
                st.push(t.equals("+")?a+b:
                        t.equals("-")?a-b:
                        t.equals("*")?a*b:a/b);
            } else st.push(Integer.parseInt(t));
        }
        return st.pop();
    }

    public static void main(String[] args) {
        System.out.println(evalRPN(new String[]{"2","1","+","3","*"}));
    }
}
