import java.io.*;
import  java.util.*;

// Read only region start
class UserMainCode
{

	public int getCodeThroughStrings(String input1){
		// Read only region end
		// Write code here...
        String word[]=input1.split(" ");
        int sum=0;
        for (int i=0;i<word.length;i++)
        {
            sum+=word[i].length();
        }
        return(1+(sum-1)%9);
    }
}
