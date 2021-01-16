import java.util.Scanner;

public class Main {

    public static void main(String[] args) {
        final byte Months = 12;
        final byte Percent = 100;

        Scanner scanner = new Scanner(System.in);

        System.out.println("Principal: ");
        float Principal = scanner.nextFloat();

        System.out.println("Annual Interest Rate: ");
        float Rate = scanner.nextFloat();
        float monthRate = Rate / Percent / Months;

        System.out.println("Period(years): ");
        float Period = scanner.nextFloat();
        float Payments = Period * Months;

        double Mortage = Principal
                * (monthRate * Math.pow(1 + monthRate, Payments)
                / (Math.pow(1 + monthRate, Payments) - 1));
        System.out.println(Mortage);


    }
}
