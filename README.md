HelloWorld
==========

public class VirtualChess {

	/*
	Hint: enums are used to express fixed sets of constants throughout your program,
	and because they are constants, we type-set them in UPPER CASE.
	Similarly, you could have enum for days of week ( MONDAY, TUESDAY...),
	compass directions (NORTH, WEST...) etc.
	*/

	
	public static void main (String [] args) {
		// create a chessboard matrix.
		//It is an array of arrays (hence matrix) of size 8 * 8
		
		Chessmen[][] chessboard = new Chessmen[8][8];
		
		//use 2 nested for loops to populate the chessboard with pieces and empty spaces
		//if...else statements should help to set the pieces where they belong.
		//chessboard[i][j] = Chessmen.EMPTY

		int i = 0;
		int j = 0;
		chessboard[i][j] = Chessmen.EMPTY;

		/*Chessmen.WHITE_KING  "wK";
		Chessmen.WHITE_QUEEN 
		Chessmen.WHITE_ROOK,
		Chessmen.WHITE_BISHOP,
		Chessmen.WHITE_KNIGHT,
		Chessmen.WHITE_PAWN,
		Chessmen.BLACK_KING,
		Chessmen.BLACK_QUEEN,
		Chessmen.BLACK_ROOK,
		Chessmen.BLACK_BISHOP,
		Chessmen.BLACK_KNIGHT,
		Chessmen.BLACK_PAWN,
		Chessmen.EMPTY,
		
		*/
		
		for (i = 0; i &lt;= 8; i++) {
			//assign
			chessboard [1][i] = Chessmen.BLACK_PAWN;
			chessboard[7][i] = Chessmen.WHITE_PAWN;
			for (j = 0; j &lt;= 8; j++) {
				if (i == 0){
					chessboard[i][0] = Chessmen.BLACK_ROOK;
					chessboard[i][1] = Chessmen.BLACK_KNIGHT;
					chessboard[i][2] = Chessmen.BLACK_BISHOP;
					chessboard[i][3] = Chessmen.BLACK_KING;
					chessboard[i][4] = Chessmen.BLACK_QUEEN;
					chessboard[i][5] = Chessmen.BLACK_BISHOP;
					chessboard[i][6] = Chessmen.BLACK_KNIGHT;
					chessboard[i][7] = Chessmen.BLACK_ROOK;
				} else if (i == 8) {
					chessboard[i][0] = Chessmen.WHITE_ROOK;
					chessboard[i][1] = Chessmen.WHITE_KNIGHT;
					chessboard[i][2] = Chessmen.WHITE_BISHOP;
					chessboard[i][3] = Chessmen.WHITE_KING;
					chessboard[i][4] = Chessmen.WHITE_QUEEN;
					chessboard[i][5] = Chessmen.WHITE_BISHOP;
					chessboard[i][6] = Chessmen.WHITE_KNIGHT;
					chessboard[i][7] = Chessmen.WHITE_ROOK;
				}
				
			}
			
		}
	}
	public enum Chessmen {
		WHITE_KING,
		WHITE_QUEEN,
		WHITE_ROOK,
		WHITE_BISHOP,
		WHITE_KNIGHT,
		WHITE_PAWN,
		BLACK_KING,
		BLACK_QUEEN,
		BLACK_ROOK,
		BLACK_BISHOP,
		BLACK_KNIGHT,
		BLACK_PAWN,
		EMPTY,
	}
	
	
	public static void printBoard (Chessmen[][] chessboard) {
		/*Use "\t" for placing tabs in strings. This will help you align
		individual columns in your chessboard.*/
		// for i rows
		for (i = 0; i &lt;= 8; i++){
			chessboard[][] = new int [][]{
		}
		
			// for j columns
				// switch(chessboard[i][j])
					// case WHITE_KING : ...
					// ...
			//end for j
				//print new line
		//end for i
	}
	
	
	
	
	
}
first repository
