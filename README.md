# Vaje
class Naloga0 {
    public static void main(String[] args) {

        for (int  a = 1; a <= 10; a++) {
            System.out.print(a + " ");
        }

        int presledek;
        for (int j = 2; j <= 10; j++) {

            System.out.println();

            presledek = 1;
            while (presledek < j) {
                System.out.print("  ");
                presledek++;
            }
            
            System.out.print(j);
        }
    }
}
