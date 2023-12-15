import java.util.Scanner;

class Player {
    private int number;
    private String position;
    private String name;

    public Player(int num, String pos, String nm) {
        this.number = num;
        this.position = pos;
        this.name = nm;
    }

    // Function to display player information
    public void displayPlayer() {
        System.out.println("Player " + number + " (" + position + "): " + name);
    }

    public int getNumber() {
        return this.number;
    }
}

public class Main {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        System.out.print("Enter the player number: ");
        int playerNumber = scanner.nextInt();

        // Array to store player information
        Player[] players = {
            new Player(7, "Left Wing", "Vini Jr"),
            new Player(9, "Center Forward", "Endrick"),
            new Player(11, "Right Wing", "Rodrygo"),
            new Player(5, "Center Attacking Midfield", "Jude Bellingham"),
            new Player(15, "Center Midfielder", "Federico Valverde"),
            new Player(23, "Center Midfielder", "Arda Guler"),
            new Player(12, "Left Back", "Eduardo Camavinga"),
            new Player(3, "Center Back", "Eder Militao"),
            new Player(16, "Center Back", "Aurelien Tchouameni"),
            new Player(19, "Right Back", "Fran Garcia"),
            new Player(1, "Goalkeeper", "Thibaut Courtois"),
            new Player(8, "Central Midfielder", "Toni Kroos"),
            new Player(10, "Central Midfielder", "Luka Modric"),
            new Player(4, "Center Back", "David Alaba"),
            new Player(2, "Right Back", "Dani Carvajal"),
            new Player(29, "Striker", "Nico Paz"),
            new Player(33, "Center Forward", "Gonzalo Garcia"),
            new Player(27, "Center Back", "Antonio Rudiger"),
        };

        // Search for the player based on the player number
        boolean playerFound = false;
        for (Player player : players) {
            if (playerNumber == player.getNumber()) {
                player.displayPlayer();
                playerFound = true;
                break;
            }
        }

        // Display message if player not found
        if (!playerFound) {
            System.out.println("Player not found.");
        }

        scanner.close();
    }
}
