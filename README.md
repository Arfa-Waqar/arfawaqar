package bookk;


public class Bookk {
    private String title;
    private String author;
    private String isbn;
     
     public String getTitle(){
         return title;   
     }
     public void setTitle(String title){
         this.title=title;
     }
      public String getAuthor(){
         return author;   
     }
     public void setAuthor(String author){
         this.author=author;
     }
      public String getIsbn(){
         return isbn;   
     }
     public void set(String isbn){
         this.isbn=isbn;
     }

    public Bookk(String title, String author, String isbn) {
        this.title = title;
        this.author = author;
        this.isbn = isbn;
    }
    
   
    public static void main(String[] args) {
        Bookk myBookk=new Bookk("Fantastic Beats","J.k","5467892345");
        System.out.println("Title:" +myBookk.title);
        System.out.println("Author:" +myBookk.author);
        System.out.println("ISBN:" +myBookk.isbn);
    }
    
}
