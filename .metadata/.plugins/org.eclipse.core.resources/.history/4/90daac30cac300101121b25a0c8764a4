public class Main {
    public static double[][] idw(double[][] data) {
        return grid.fill(data);
    }

    public static void main(String[] matrix) {
        double[][] input = {
                {1.0, Double.NaN, 3.0},
                {Double.NaN, Double.NaN, 2.0},
                {4.0, 5.0, Double.NaN}
        };
        double[][] output = idw(input);

        for (int i = 0; i < output.length; i++) {
            for (int j = 0; j < output[i].length; j++) {
            	 System.out.println(output[i][j]);             
            }
        }
    }
}