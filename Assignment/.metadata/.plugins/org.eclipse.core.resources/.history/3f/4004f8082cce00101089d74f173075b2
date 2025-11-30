public class IDW {
	public static double calculate(double[][] data, int r, int c) {
		double above = 0;
		double below = 0;
		double result = 0;
		for (int i = 0; i < data.length; i++) {
			for (int j = 0; j < data[0].length; j++) {
				double t = data[i][j];
				if (!Double.isNaN(t)) {
					double dis = Distance.dis(r, c, i, j);
					if (dis == 0) {
						return t;
					}
					double s = 1 / (dis * dis);
					above += s * t;
					below += s;
				}
			}
		}
		if (below == 0) {
			return Double.NaN;
		} else {
			result = above / below;
			return result;
		}
	}
}