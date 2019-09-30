package JavaExceptions;

public class ExceptionArray {
    public static void main(String[] args) {
        int[] myArr = {12,1234134,34534,2346,5756,32453,667,4564,3533,242,1778,97867,5645};
        try
        {
            System.out.println(myArr[15]);
        }
        catch (Exception e){
            System.err.println("You just exceeded the index bound, try again");
        }
        for(int numbers:myArr){
            System.out.println(numbers);
        }

    }
}
