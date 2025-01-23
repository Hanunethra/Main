# Main
public class Main {
public int addition(int x, int y) {
    return x + y;
  }

  // method to add three integers
  public int addition(int x, int y, int z) {
    return x + y + z;
  }

  // method to add two doubles
  public double addition(double x, double y) {
    return x + y;
  }
    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        // TODO code application logic here
         Main number = new Main();

    // calling the overloaded methods
    int res1 = number.addition(22,88);
    System.out.println("Addition of two integers: " + res1);

    int res2 = number.addition(24,78,45);
    System.out.println("Addition of three integers: " + res2);

    double res3 = number.addition(10.15, 20.22);
    System.out.println("Addition of two doubles: " + res3);
    }

Output:

Addition of two integers: 110
Addition of three integers: 147
Addition of two doubles: 30.369999999999997

