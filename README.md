# Leetcode-notes
public void inorder_print(Node root) {
		if(root==null) {
			return;
		}
		inorder_print(root.left);
		System.out.print(root.key+" ");
		inorder_print(root.right);
	}
  System.out.println{
  if (){
  
  class BST{
	Node root;
	//1111   function to add nodes to a BST
	public Node add(Node root, int key) {
		Node newNode=new Node(key);
		if(root==null) {
			root=newNode;
			return root;
		}
		if(key<root.key) {
			root.left=add(root.left,key);
		}else {
			root.right=add(root.right,key);
		}
		return root;
	}
  Sysfsdfg 总今：
  }
