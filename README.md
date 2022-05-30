# YesOrNo
Complete the method that takes a boolean value and return a "Yes" string for true, or a "No" string for false.
My solution
class YesOrNo
{
    public static String boolToWord(boolean b)
    {
        if (b==true)
        {
            return ("Yes");
        }
        else
            return ("No");
    }

}

Beautiful solution 
class YesOrNo
{
  public static String boolToWord(boolean b)
  {
    if(b) return "Yes";
    else return "No";
  }
  
}
