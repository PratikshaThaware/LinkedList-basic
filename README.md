# LinkedList-basic
class Node{
    int data;
    Node next;
    public Node(int data){
        this.data = data;
        
    }
    public static void main(String []args){
        Node one = new Node(1);
        Node two = new Node(2);
        Node three = new Node(3);
        System.out.println(two.data+" "+two.next);
    }
}

Basic Program:


class Node{
    int data;
    Node next;
    public Node(int data){
        this.data = data;
        
    }
    public static void main(String []args){
        Node one = new Node(1);
        Node two = new Node(2);
        Node three = new Node(3);
       one.next = two;
       two.next = three;
       System.out.println(one.data+" "+one.next.data+" "+one.next.next.data);
    }
}
output:1 2 3

Print Data:Program:

class Node{
 
    int data;
    Node next;
    public Node(int data){
        this.data = data;
        
    
}
public void printLL(Node head){
    while(head != null){
        System.out.println(head.data);
        head = head.next;
    }
}
    
    public static void main(String []args){
        Node one = new Node(1);
        Node two = new Node(2);
        Node three = new Node(3);
       one.next = two;
       two.next = three;
       System.out.println(one.data+" "+one.next.data+" "+one.next.next.data);
    }
}
output: 1 2 3

