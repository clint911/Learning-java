# Learning-java
Useful snippets for learning java
//multi-dimensional arrays in java
package Hello2;
//multi-dimensional arrays
public class HelloApp6 {
    public static void main(String[] args){
        String[][] cars = new String[3][3];

        cars[0][0] = "Camero";
        cars[0][1] = "courvette";
        cars[0][2] = "Silverado";
        cars[1][0] = "Mustang";
        cars[1][1] = "Ranger";
        cars[1][2]= "F1-250";
        cars[2][0] = "Ferrari";
        cars[2][1] = "Lambo";
        cars[2][2]= "Tesla";
        //using a nested for loop to iterate through the values of
        //our two dimensional array
        for(int i = 0; i  < cars.length;i++){
            System.out.println();
            for(int j = 0; j < cars[i].length; j++){
                System.out.print(cars[i][j]+"");
            }
        }
    }
}
