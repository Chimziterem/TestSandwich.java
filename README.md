# TestSandwich.java

class TestSandwich
{
  public static void main (String args[])
  {
    Sandwich sandwich = new Sandwich();
    sandwich.setMainIngredient("tuna");
    sandwich.setBread("wheat");
    sandwich.setPrice(4.99);
    System.out.println("You have ordered a " + 
        sandwich.getMainIngredient() + " Sandwich on " + 
        sandwich.getBread() + " Bread, and the Price is " + sandwich.getPrice());
  }
}
