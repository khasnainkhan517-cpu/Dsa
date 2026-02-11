public class RemoveLinkedListElements {
    static class ListNode {
        int val; ListNode next;
        ListNode(int v){val=v;}
    }

    static ListNode removeElements(ListNode head, int val) {
        ListNode dummy = new ListNode(0);
        dummy.next = head;
        ListNode cur = dummy;
        while(cur.next!=null){
            if(cur.next.val==val) cur.next=cur.next.next;
            else cur=cur.next;
        }
        return dummy.next;
    }

    public static void main(String[] args) {}
}
