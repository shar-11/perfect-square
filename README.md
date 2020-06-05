# perfect-square
    Import java.util.scanner;
    Class javaexample{
         Static Boolean checkperfectsquare(double)
         {
            Double sq=math.sqrt(x);
            Return((sq-math.floor(sq))==0);
          }
        Public static void main(string[]args)
         {
           System.out.println("enter any number");
           Scanner scanner=new scanner(system.in);
           Double num=scanner.nextdouble();
           Scanner.close();
          If(checkperfectsquare(num))
              System.out.println(num+"is a perfect square number");
          Else
               System.out.println(num+"is not a perfect square number");
          }
