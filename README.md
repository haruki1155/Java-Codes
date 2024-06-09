import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        int quantity, num;
        float price, temp;
        char code;

        System.out.println("WELCOME!\n\n");
        System.out.println("\"Main Menu\"\n");
        System.out.println("1.| [🥤 Soda]  \n");
        System.out.println("2.| [🍔 Burger]  \n");
        System.out.println("3.| [🍗 Chicken] \n");
        System.out.println("4.| [🍝 Pasta]  \n\n");
        System.out.print("Select a Number: ");
        code = scanner.next().charAt(0);

        if (code == '1') {
            System.out.println("Selected- Soda Menu\n\n");
            System.out.println("1. Coke ......₱ 25\n");
            System.out.println("2. Pepsi......₱ 28\n");
            System.out.println("3. RC   ......₱ 26\n\n");
            System.out.println("Please select your drink.\n");

            char sodaChoice;
            System.out.print("\n\nSelected Number: ");
            sodaChoice = scanner.next().charAt(0);
            switch (sodaChoice) {
                case '1':
                    System.out.println("Coke Selected" + "\n");
                    temp = 25;
                    break;
                case '2':
                    System.out.println("Pepsi Selected" + "\n");
                    temp = 28;
                    break;
                case '3':
                    System.out.println("RC Selected" + "\n");
                    temp = 26;
                    break;
                default:
                    System.out.println("Invalid choice. Please try again." + "\n");
                    return;
            }

            System.out.print("Enter Any Quantity: " + "\n");
            quantity = scanner.nextInt();
            price = temp * quantity;
            System.out.println("Total Price: ₱ " + price + "\n");
            System.out.println("Please Pay at the counter, THANK YOU & COME AGAIN ❤️ ! " + "\n");
            if (quantity <= 0) {
                System.out.println("Invalid" + "\n");
            } else if (quantity > 0) {
                System.out.println("Quantity Selected: " + quantity + "\n");
            } else {
                System.out.println("Invalid" + "\n");
            }
        } else if (code == '2') {
            System.out.println("Selected- Burger Menu\n\n");
            System.out.println("1. Regular Burger: ₱25\n");
            System.out.println("2. Cheese Burger: ₱35\n");
            System.out.println("3. Ham & Egg Burger: ₱50\n\n");
            System.out.println("Please select your Burger." + "\n");
            char burgerChoice;
            System.out.print("\n\nSelect a Number: ");
            burgerChoice = scanner.next().charAt(0);
            switch (burgerChoice) {
                case '1':
                    System.out.println("Regular Burger Selected" + "\n");
                    temp = 25;
                    break;
                case '2':
                    System.out.println("Cheese Burger Selected" + "\n");
                    temp = 35;
                    break;
                case '3':
                    System.out.println("Ham & Egg Burger Selected" + "\n");
                    temp = 50;
                    break;
                default:
                    System.out.println("Invalid choice. Please try again." + "\n");
                    return;
            }
            System.out.print("Enter Any Quantity: " + "\n");
            quantity = scanner.nextInt();
            price = temp * quantity;
            System.out.println("Total Price: ₱ " + price + "\n");
            System.out.println("Please Pay at the counter, THANK YOU & COME AGAIN ❤️ ! " + "\n");
            if (quantity <= 0) {
                System.out.println("Invalid" + "\n");
            } else if (quantity > 0) {
                System.out.println("Quantity Selected: " + quantity + "\n");
            } else {
                System.out.println("Invalid" + "\n");
            }
        } else if (code == '3') {
            System.out.println("Selected- Chicken Menu\n\n");
            System.out.println("1. Crispy Fried Chicken: ₱60\n");
            System.out.println("2. Chicken BBQ: ₱75\n");
            System.out.println("3. Buttered Chicken: ₱85\n\n");
            System.out.println("Choose your Desired order!." + "\n");
            char ChickenChoice;
            System.out.print("\n\nSelect a Number: ");
            ChickenChoice = scanner.next().charAt(0);
            switch (ChickenChoice) {
                case '1':
                    System.out.println("Crispy Fried Chicken Selected" + "\n");
                    temp = 60;
                    break;
                case '2':
                    System.out.println("Chicken BBQ Selected" + "\n");
                    temp = 75;
                    break;
                case '3':
                    System.out.println("Buttered Chicken Selected" + "\n");
                    temp = 85;
                    break;
                default:
                    System.out.println("Invalid choice. Please try again." + "\n");
                    return;
            }
            System.out.print("Enter Any Quantity: " + "\n");
            quantity = scanner.nextInt();
            price = temp * quantity;
            System.out.println("Total Price: ₱ " + price + "\n");
            System.out.println("Please Pay at the counter, THANK YOU & COME AGAIN ❤️ ! " + "\n");
            if (quantity <= 0) {
                System.out.println("Invalid" + "\n");
            } else if (quantity > 0) {
                System.out.println("Quantity Selected: " + quantity + "\n");
            } else {
                System.out.println("Invalid" + "\n");
            }
        } else if (code == '4') {
            System.out.println("Selected- Pasta\n\n");
            System.out.println("1. Italian Pasta: ₱120\n");
            System.out.println("2. Cream Cheese Pasta: ₱160\n");
            System.out.println("3. Pesto Pasta: ₱175\n");

            char pastaChoice;
            System.out.print("\n\nSelect a Number: ");
            pastaChoice = scanner.next().charAt(0);
            switch (pastaChoice) {
                case '1':
                    System.out.println("Italian Pasta Selected" + "\n");
                    temp = 120;
                    break;
                case '2':
                    System.out.println("Cream Cheese Pasta Selected" + "\n");
                    temp = 160;
                    break;
                case '3':
                    System.out.println("Pest Pasta Selected" + "\n");
                    temp = 175;
                    break;
                default:
                    System.out.println("Invalid choice. Please Try Again! " + "\n");
                    return;
            }
            System.out.print("Enter Any Quantity: " + "\n");
            quantity = scanner.nextInt();
            price = temp * quantity;
            System.out.println("Total Price: ₱ " + price + "\n");
            System.out.println("Please Pay at the counter, THANK YOU & COME AGAIN ❤️ ! " + "\n");
            if (quantity <= 0) {
                System.out.println("Invalid" + "\n");
            } else if (quantity > 0) {
                System.out.println("Quantity Selected: " + quantity + " " + "\n");
            } else {
                System.out.println("Invalid" + "\n");
            }
        } else {
            System.out.println("Invalid choice. Please try again." + "\n");
        }

        scanner.close();
    }
}
