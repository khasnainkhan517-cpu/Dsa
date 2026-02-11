import java.util.*;

public class MinStack {
    Stack<Integer> s=new Stack<>();
    Stack<Integer> min=new Stack<>();

    void push(int x){
        s.push(x);
        if(min.isEmpty() || x<=min.peek()) min.push(x);
    }
    void pop(){
        if(s.pop().equals(min.peek())) min.pop();
    }
    int top(){ return s.peek(); }
    int getMin(){ return min.peek(); }

    public static void main(String[] args) {
        MinStack ms=new MinStack();
        ms.push(5); ms.push(3); ms.push(2);
        System.out.println(ms.getMin());
    }
}
