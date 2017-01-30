
import java.io.BufferedReader;
import java.io.InputStreamReader;


class abc {

    public static void main(String[] args) throws Exception {
        
        InputStreamReader isr = new InputStreamReader(System.in);
        BufferedReader br =new BufferedReader(isr);
      
        
        int a[] = new int[10];
        for (int i = 0; i < a.length; i++) {
            System.out.println("enter a number");
            a[i] = Integer.parseInt(br.readLine());
        }
        int c = 0, flag = 0, pos = -1;
        System.out.println("Enter a number to be searched");
        c= Integer.parseInt (br.readLine());
        for (int i = 0; i < a.length; i++) {
            if (c == a[i]) {
                flag = 1;
                pos = i + 1;
            }
        }
        if (flag == 0) {
            System.out.println("Number not found!!!");
        } else {
            System.out.println("Number is found at position " + pos);
        }
    }
}
