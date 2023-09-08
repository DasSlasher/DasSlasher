public class Platin
{
    public static void main(String str)
    {
        int x,y;
        String str1, str2;
        char b=0;
        x=str.length();
        System.out.println("The Pig Latin of the word = ");
        for(y=0;y<x;y++)
        {
            b=(str.charAt(y));
            if (b=='a'||b=='e'||b=='i'||b=='o'||b=='u'||b=='A'||b=='E'||b=='I'||b=='O'||b=='U')
            break;
        }
        str1=str.substring(y,x);
        str2=str.substring(0,y);
        System.out.println(str1+str2+"ay");
        }
    }
