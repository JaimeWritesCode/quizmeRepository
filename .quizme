import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);

        System.out.println("Welcome to Quiz Me!");
        System.out.println("This project is made by Jaime Lorenzo Solis Palacio");
        System.out.println("------------------------------------------------");

        System.out.print("What is your name?: ");
        String yourName = input.nextLine();
        System.out.println("------------------------------------------------");

        System.out.print("Select a quiz number [0, 1, 2]: ");
        int numberSelection = input.nextInt();
        input.nextLine();
        System.out.println("------------------------------------------------");

        int result = 0;


        //Quiz 0 (1 - 10)

        while (numberSelection == 0) {
            System.out.print(yourName + " What is the letter after a?: ");
            String letter = input.nextLine();
            if (letter.equalsIgnoreCase("b")) {
                System.out.println("Correct!" + " 1 point!");
                break;
            } else {
                System.out.println(yourName + " Please try again!" + " Number of points: [0]");
                System.out.println("------------------------------------------------");
            }
        }


        while (numberSelection == 0) {
            System.out.println("------------------------------------------------");
            System.out.print(yourName + " What is the capital of the Philippines: ");
            String capital = input.nextLine();
            if (capital.equalsIgnoreCase("Manila")) {
                System.out.println("Correct!" + " 2 points accumulated!");
                System.out.println("------------------------------------------------");
                break;
            } else {
                System.out.println(yourName + " Please try again!" + " Number of points: [1]");
                System.out.println("------------------------------------------------");
            }
        }

        while (numberSelection == 0) {
            System.out.print(yourName + " What is the full name of Jose Rizal?: ");
            String fullName = input.nextLine();
            if (fullName.equalsIgnoreCase("jose protasio rizal mercado y alonso realonda") || fullName.equalsIgnoreCase("jose protacio rizal mercado y alonso realonda")) {
                System.out.println("Correct!" + " 3 points accumulated!");
                System.out.println("------------------------------------------------");
                break;
            } else {
                System.out.println(yourName + " Please try again!" + " Number of points: [2]");
                System.out.println("------------------------------------------------");
            }
        }

        while (numberSelection == 0) {
            System.out.print(yourName + " What is the nickname  of Jaime from IT1B?: ");
            String nickName = input.nextLine();
            if (nickName.equalsIgnoreCase("Enzo")) {
                System.out.println("Correct!" + " 4 points accumulated!");
                System.out.println("------------------------------------------------");
                break;
            } else {
                System.out.println(yourName + " Do you even know me? ");
                System.out.println("*SIGH*");
                System.out.println(" Number of points: [3]");
                System.out.println("------------------------------------------------");
            }
        }

        while (numberSelection == 0) {
            System.out.print(yourName + " It is the powerhouse of the cell: ");
            String powerHouse = input.nextLine();

            if (powerHouse.equalsIgnoreCase("mitochondria")) {
                System.out.println("Correct!" + " 5 points accumulated!");
                result = 5;
                System.out.println("------------------------------------------------");
                break;
            } else {
                System.out.println(yourName + " You are correct! De joke lang" + " Please try again!");
                System.out.println("Number of points: [4]");
                result = 4;
                System.out.println("------------------------------------------------");
            }
        }

        while (numberSelection == 0) {
            System.out.print(yourName + " How many years did the Spanish rule the Philippines? (Number(s) Only): ");
            int rulingYears = input.nextInt();

            if (rulingYears == 333) {
                System.out.println("Correct" + " 6 points accumulated");
                result = 6;
                System.out.println("------------------------------------------------");
                break;
            } else {
                System.out.println(yourName + " Please try again!" + " Number of points: [5]");
                result = 5;
                System.out.println("------------------------------------------------");
            }
        }

            while (numberSelection == 0) {
                System.out.println(yourName + " What is the meaning of the KKK in the Philippine revolutionary flag that was lead by Andres Bonifacio?: ");
                String kkk = input.nextLine();

                if(kkk.equalsIgnoreCase("Kataastaasan, Kagalanggalang Na Katipunan Ng Mga Anak Ng Bayan") || kkk.equalsIgnoreCase("Kataastaasan Kagalanggalang Na Katipunan Ng Mga Anak Ng Bayan") || kkk.equalsIgnoreCase("Kataastaasan Kagalanggalangang Na Katipunan Ng Mga Anak Ng Bayan") || kkk.equalsIgnoreCase("Kataastaasan, Kagalanggalangang Na Katipunan Ng Mga Anak Ng Bayan") || kkk.equalsIgnoreCase("Kataastaasan, Kagalang-galangang Katipunan ng mga Anak ng Bayan") || kkk.equalsIgnoreCase("Kataastaasan, Kagalanggalangang Katipunan ng mga Anak ng Bayan") || kkk.equalsIgnoreCase("Kataastaasan Kagalanggalangang Katipunan ng mga Anak ng Bayan") || kkk.equalsIgnoreCase("Kataastaasan Kagalang-galangang Katipunan ng mga Anak ng Bayan")){
                    System.out.println(yourName + " You are good at this!" + " Number of points: [7]");
                    result = 7;
                    System.out.println("------------------------------------------------");
                    break;
                } else {
                    System.out.println("Wrong!");
                    System.out.println(yourName + " Please try again!" + " Accumulated points: [6]");
                    result = 6;
                    System.out.println("------------------------------------------------");
                }
            }

            while (numberSelection == 0){
                System.out.print(yourName + " It is a google application/website where you can store your files, images and videos: ");
                String googleDrive = input.nextLine();

                if(googleDrive.equalsIgnoreCase("google drive")){
                    System.out.println("You are correct! " + yourName);
                    System.out.println("Accumulated points: [8]");
                    result = 8;
                    System.out.println("------------------------------------------------");
                    break;
                } else {
                    System.out.println("Please try again...");
                    System.out.println("Accumulated points: [7]");
                    System.out.println("------------------------------------------------");
                }
            }

            while (numberSelection == 0){
                System.out.print("An apple a day keeps the [blank] away: ");
                String doctor = input.nextLine();

                if(doctor.equalsIgnoreCase("doctor")){
                    System.out.println("Niceeeeeee");
                    System.out.println(yourName + " You have accumulated [9] points!");
                    System.out.println("------------------------------------------------");
                    break;
                } else {
                    System.out.println("ehhhhh?");
                    System.out.println("Accumulated points: [8]");
                    System.out.println("------------------------------------------------");
                }
            }

            while(numberSelection == 0){
                System.out.print("[Blank] is a wave that is capable of transmitting its energy through a vacuum: ");
                String wave = input.nextLine();

                if(wave.equalsIgnoreCase("electromagnetic wave") || wave.equalsIgnoreCase("electromagnetic waves")){
                    System.out.println("Correct!");
                    System.out.println("Quiz 0 has been completed!");
                    result = 10;
                    System.out.println(yourName + " You have accumulated [10] points!");
                    System.out.println("------------------------------------------------");
                    break;
                } else {
                    System.out.println("Your answer is wrong.");
                    result = 9;
                    System.out.println(yourName + " You have accumulated [9] points!");
                    System.out.println("Nobody is perfect but that doesn't mean we can't celebrate our accomplishments -Jaime");
                    System.out.println("------------------------------------------------");
                }
            }

            //Quiz 1 (1 - 10)

            while(numberSelection == 1){
                System.out.print(yourName + ", What is the name of the ninja anime in which the main character wants to become the Hokage?: ");
                String ninja = input.nextLine();

                if(ninja.equalsIgnoreCase("Naruto")){
                    System.out.println("Correct!");
                    result = 1;
                    System.out.println("Accumulated points:" + "[" + result + "]");
                    System.out.println("------------------------------------------------");
                    break;
                } else {
                    System.out.println(ninja + " is incorrect..");
                    System.out.println("Please try again!");
                    result = 0;
                    System.out.println("Accumulated points:" + "[" + result + "]");
                    System.out.println("------------------------------------------------");
                }
            }

            while(numberSelection == 1){
                System.out.print(yourName + ", What do you call a chair in tagalog?: ");
                String theChair = input.nextLine();

                if(theChair.equalsIgnoreCase("salumpuwit")){
                    System.out.println("Ang " + theChair + " ay tama!");
                    result = 2;
                    System.out.println("Accumulated points:" + "[" + result + "]");
                    System.out.println("------------------------------------------------");
                    break;
                } else {
                    System.out.println("Huwag kana ulit magkamali tulad kung paano ka nagkamali sa kanya...");
                    System.out.println("Subukan ninyo muli!");
                    result = 1;
                    System.out.println("Accumulated points:" + "[" + result + "]");
                    System.out.println("------------------------------------------------");
                }
            }

            while(numberSelection == 1){
                System.out.print("The Philippine is flipped with the red part being on top during times of [BLANK]: ");
                String redPart = input.nextLine();

                if(redPart.equalsIgnoreCase("war") || redPart.equalsIgnoreCase("times of war")){
                    System.out.println("Correct!");
                    System.out.println("You sure are patriotic");
                    result = 3;
                    System.out.println("Accumulated points:" + "[" + result + "]");
                    System.out.println("------------------------------------------------");
                    break;
                } else {
                    System.out.println("You "+ yourName + ", are unfortunately wrong.");
                    System.out.println("Please try again!");
                    result = 2;
                    System.out.println("Accumulated points:" + "[" + result + "]");
                    System.out.println("------------------------------------------------");
                }
            }

            while(numberSelection == 1){
                System.out.println("");
            }


            System.out.println(yourName + " Congratulations on getting " + "[" + result + "]" + " points!");
            System.out.println("Thank you for playing Quiz Me!");
            System.out.println("NOTE: Restart the game to try out other quizzes!");
            input.close();
            System.out.println("------------------------------------------------");
        }
    }
