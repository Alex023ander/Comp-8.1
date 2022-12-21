# Comp-8.1

public static void main(String[] args) {
            
            Scanner scan = new Scanner(System.in);
            int[] integs = new int[51];
            System.out.println("Enter integers 0 - 50 [enter out of bounds number to quit]: ");
            int nums = scan.nextInt();
            while (nums != -1 && nums >= -0 && nums <= 50) {
            integs[nums]++;
            nums = scan.nextInt();
            }
            for (int index = 0; index <= 50; index++) {
                if (integs[index] > 0) {
                System.out.println(index + " : " + integs[index]);
                }
            }
        }

}
