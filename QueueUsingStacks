import java.util.*;

public class QueueUsingStacks {
    Stack<Integer> s1=new Stack<>(), s2=new Stack<>();

    void push(int x){ s1.push(x); }

    int pop(){
        peek();
        return s2.pop();
    }

    int peek(){
        if(s2.isEmpty())
            while(!s1.isEmpty()) s2.push(s1.pop());
        return s2.peek();
    }

    boolean empty(){ return s1.isEmpty() && s2.isEmpty(); }

    public static void main(String[] args) {}
}
