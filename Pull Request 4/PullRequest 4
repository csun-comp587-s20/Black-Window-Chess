package BlackWindow-Chess;

import static org.junit.Assert.assertEquals;

import java.util.ArrayList;
import java.util.List;

import org.junit.Test;

public class BlackWidow-ChessTest {
  
  @Test
  public void whiteplayer(){
    
  }
  
  @Test
  public void blackplayer(){
    
  }
  
  @Test
  public void player(){
    
  }
  
  @Test
  public void board(){
    
  }
  
  @Test
  public void boardutils(){
    
  }
  
  @Test
  public void move(){
    
  }
  
  @Test
  public void movetransition(){
    
  }
  
  @Test
  public void moveutils(){
    
  }
  
  @Test
  public void piece(){
    
  }
  
  @Test
  public void pieceUtils(){
    
  }
  
  @Test
  public void king(){
	  final Board.Builder builder = new Board.Builder();
      // Black Layout
      builder.setPiece(new King(Alliance.BLACK, 4, false, false));
      // White Layout
      builder.setPiece(new King(Alliance.WHITE, 36));
      builder.setPiece(new King(Alliance.WHITE, 60, false, false));
      // Set the current player
      builder.setMoveMaker(Alliance.WHITE);
      final Board board = builder.build();
      final Collection<Move> whiteLegals = board.whitePlayer().getLegalMoves();
      final Collection<Move> blackLegals = board.blackPlayer().getLegalMoves();
      assertEquals(whiteLegals.size(), 18);
      assertEquals(blackLegals.size(), 5);
      assertTrue(whiteLegals.contains(Move.MoveFactory
              .createMove(board, BoardUtils.INSTANCE.getCoordinateAtPosition("e4"), BoardUtils.INSTANCE.getCoordinateAtPosition("e8"))));
      assertTrue(whiteLegals.contains(Move.MoveFactory
              .createMove(board, BoardUtils.INSTANCE.getCoordinateAtPosition("e4"), BoardUtils.INSTANCE.getCoordinateAtPosition("e7"))));
      assertTrue(whiteLegals.contains(Move.MoveFactory
              .createMove(board, BoardUtils.INSTANCE.getCoordinateAtPosition("e4"), BoardUtils.INSTANCE.getCoordinateAtPosition("e6"))));
      assertTrue(whiteLegals.contains(Move.MoveFactory
              .createMove(board, BoardUtils.INSTANCE.getCoordinateAtPosition("e4"), BoardUtils.INSTANCE.getCoordinateAtPosition("e5"))));
      assertTrue(whiteLegals.contains(Move.MoveFactory
              .createMove(board, BoardUtils.INSTANCE.getCoordinateAtPosition("e4"), BoardUtils.INSTANCE.getCoordinateAtPosition("e3"))));
      assertTrue(whiteLegals.contains(Move.MoveFactory
              .createMove(board, BoardUtils.INSTANCE.getCoordinateAtPosition("e4"), BoardUtils.INSTANCE.getCoordinateAtPosition("e2"))));
      assertTrue(whiteLegals.contains(Move.MoveFactory
              .createMove(board, BoardUtils.INSTANCE.getCoordinateAtPosition("e4"), BoardUtils.INSTANCE.getCoordinateAtPosition("a4"))));
      assertTrue(whiteLegals.contains(Move.MoveFactory
              .createMove(board, BoardUtils.INSTANCE.getCoordinateAtPosition("e4"), BoardUtils.INSTANCE.getCoordinateAtPosition("b4"))));
      assertTrue(whiteLegals.contains(Move.MoveFactory
              .createMove(board, BoardUtils.INSTANCE.getCoordinateAtPosition("e4"), BoardUtils.INSTANCE.getCoordinateAtPosition("c4"))));
      assertTrue(whiteLegals.contains(Move.MoveFactory
              .createMove(board, BoardUtils.INSTANCE.getCoordinateAtPosition("e4"), BoardUtils.INSTANCE.getCoordinateAtPosition("d4"))));
      assertTrue(whiteLegals.contains(Move.MoveFactory
              .createMove(board, BoardUtils.INSTANCE.getCoordinateAtPosition("e4"), BoardUtils.INSTANCE.getCoordinateAtPosition("f4"))));
      assertTrue(whiteLegals.contains(Move.MoveFactory
              .createMove(board, BoardUtils.INSTANCE.getCoordinateAtPosition("e4"), BoardUtils.INSTANCE.getCoordinateAtPosition("g4"))));
      assertTrue(whiteLegals.contains(Move.MoveFactory
              .createMove(board, BoardUtils.INSTANCE.getCoordinateAtPosition("e4"), BoardUtils.INSTANCE.getCoordinateAtPosition("h4"))));
  }
  
  @Test
  public void queen(){
        final Board.Builder builder = new Board.Builder();
        // Black Layout
        builder.setPiece(new King(Alliance.BLACK, 4, false, false));
        // White Layout
        builder.setPiece(new Queen(Alliance.WHITE, 36));
        builder.setPiece(new King(Alliance.WHITE, 60, false, false));
        // Set the current player
        builder.setMoveMaker(Alliance.WHITE);
        final Board board = builder.build();
        final Collection<Move> whiteLegals = board.whitePlayer().getLegalMoves();
        final Collection<Move> blackLegals = board.blackPlayer().getLegalMoves();
        assertEquals(whiteLegals.size(), 31);
        assertEquals(blackLegals.size(), 5);
        assertTrue(whiteLegals.contains(Move.MoveFactory
                .createMove(board, BoardUtils.INSTANCE.getCoordinateAtPosition("e4"), BoardUtils.INSTANCE.getCoordinateAtPosition("e8"))));
        assertTrue(whiteLegals.contains(Move.MoveFactory
                .createMove(board, BoardUtils.INSTANCE.getCoordinateAtPosition("e4"), BoardUtils.INSTANCE.getCoordinateAtPosition("e7"))));
        assertTrue(whiteLegals.contains(Move.MoveFactory
                .createMove(board, BoardUtils.INSTANCE.getCoordinateAtPosition("e4"), BoardUtils.INSTANCE.getCoordinateAtPosition("e6"))));
        assertTrue(whiteLegals.contains(Move.MoveFactory
                .createMove(board, BoardUtils.INSTANCE.getCoordinateAtPosition("e4"), BoardUtils.INSTANCE.getCoordinateAtPosition("e5"))));
        assertTrue(whiteLegals.contains(Move.MoveFactory
                .createMove(board, BoardUtils.INSTANCE.getCoordinateAtPosition("e4"), BoardUtils.INSTANCE.getCoordinateAtPosition("e3"))));
        assertTrue(whiteLegals.contains(Move.MoveFactory
                .createMove(board, BoardUtils.INSTANCE.getCoordinateAtPosition("e4"), BoardUtils.INSTANCE.getCoordinateAtPosition("e2"))));
        assertTrue(whiteLegals.contains(Move.MoveFactory
                .createMove(board, BoardUtils.INSTANCE.getCoordinateAtPosition("e4"), BoardUtils.INSTANCE.getCoordinateAtPosition("a4"))));
        assertTrue(whiteLegals.contains(Move.MoveFactory
                .createMove(board, BoardUtils.INSTANCE.getCoordinateAtPosition("e4"), BoardUtils.INSTANCE.getCoordinateAtPosition("b4"))));
        assertTrue(whiteLegals.contains(Move.MoveFactory
                .createMove(board, BoardUtils.INSTANCE.getCoordinateAtPosition("e4"), BoardUtils.INSTANCE.getCoordinateAtPosition("c4"))));
        assertTrue(whiteLegals.contains(Move.MoveFactory
                .createMove(board, BoardUtils.INSTANCE.getCoordinateAtPosition("e4"), BoardUtils.INSTANCE.getCoordinateAtPosition("d4"))));
        assertTrue(whiteLegals.contains(Move.MoveFactory
                .createMove(board, BoardUtils.INSTANCE.getCoordinateAtPosition("e4"), BoardUtils.INSTANCE.getCoordinateAtPosition("f4"))));
        assertTrue(whiteLegals.contains(Move.MoveFactory
                .createMove(board, BoardUtils.INSTANCE.getCoordinateAtPosition("e4"), BoardUtils.INSTANCE.getCoordinateAtPosition("g4"))));
        assertTrue(whiteLegals.contains(Move.MoveFactory
                .createMove(board, BoardUtils.INSTANCE.getCoordinateAtPosition("e4"), BoardUtils.INSTANCE.getCoordinateAtPosition("h4"))));
    }
  
  @Test
  public void rooks(){
        final Board.Builder builder = new Board.Builder();
        // Black Layout
        builder.setPiece(new King(Alliance.BLACK, 4, false, false));
        // White Layout
        builder.setPiece(new Rook(Alliance.WHITE, 36));
        builder.setPiece(new King(Alliance.WHITE, 60, false, false));
        // Set the current player
        builder.setMoveMaker(Alliance.WHITE);
        final Board board = builder.build();
        final Collection<Move> whiteLegals = board.whitePlayer().getLegalMoves();
        final Collection<Move> blackLegals = board.blackPlayer().getLegalMoves();
        assertEquals(whiteLegals.size(), 18);
        assertEquals(blackLegals.size(), 5);
        assertTrue(whiteLegals.contains(Move.MoveFactory
                .createMove(board, BoardUtils.INSTANCE.getCoordinateAtPosition("e4"), BoardUtils.INSTANCE.getCoordinateAtPosition("e8"))));
        assertTrue(whiteLegals.contains(Move.MoveFactory
                .createMove(board, BoardUtils.INSTANCE.getCoordinateAtPosition("e4"), BoardUtils.INSTANCE.getCoordinateAtPosition("e7"))));
        assertTrue(whiteLegals.contains(Move.MoveFactory
                .createMove(board, BoardUtils.INSTANCE.getCoordinateAtPosition("e4"), BoardUtils.INSTANCE.getCoordinateAtPosition("e6"))));
        assertTrue(whiteLegals.contains(Move.MoveFactory
                .createMove(board, BoardUtils.INSTANCE.getCoordinateAtPosition("e4"), BoardUtils.INSTANCE.getCoordinateAtPosition("e5"))));
        assertTrue(whiteLegals.contains(Move.MoveFactory
                .createMove(board, BoardUtils.INSTANCE.getCoordinateAtPosition("e4"), BoardUtils.INSTANCE.getCoordinateAtPosition("e3"))));
        assertTrue(whiteLegals.contains(Move.MoveFactory
                .createMove(board, BoardUtils.INSTANCE.getCoordinateAtPosition("e4"), BoardUtils.INSTANCE.getCoordinateAtPosition("e2"))));
        assertTrue(whiteLegals.contains(Move.MoveFactory
                .createMove(board, BoardUtils.INSTANCE.getCoordinateAtPosition("e4"), BoardUtils.INSTANCE.getCoordinateAtPosition("a4"))));
        assertTrue(whiteLegals.contains(Move.MoveFactory
                .createMove(board, BoardUtils.INSTANCE.getCoordinateAtPosition("e4"), BoardUtils.INSTANCE.getCoordinateAtPosition("b4"))));
        assertTrue(whiteLegals.contains(Move.MoveFactory
                .createMove(board, BoardUtils.INSTANCE.getCoordinateAtPosition("e4"), BoardUtils.INSTANCE.getCoordinateAtPosition("c4"))));
        assertTrue(whiteLegals.contains(Move.MoveFactory
                .createMove(board, BoardUtils.INSTANCE.getCoordinateAtPosition("e4"), BoardUtils.INSTANCE.getCoordinateAtPosition("d4"))));
        assertTrue(whiteLegals.contains(Move.MoveFactory
                .createMove(board, BoardUtils.INSTANCE.getCoordinateAtPosition("e4"), BoardUtils.INSTANCE.getCoordinateAtPosition("f4"))));
        assertTrue(whiteLegals.contains(Move.MoveFactory
                .createMove(board, BoardUtils.INSTANCE.getCoordinateAtPosition("e4"), BoardUtils.INSTANCE.getCoordinateAtPosition("g4"))));
        assertTrue(whiteLegals.contains(Move.MoveFactory
                .createMove(board, BoardUtils.INSTANCE.getCoordinateAtPosition("e4"), BoardUtils.INSTANCE.getCoordinateAtPosition("h4"))));
    }
  
  @Test
  public void bishops(){
        Board.Builder builder = new Board.Builder();
        // Black Layout
        builder.setPiece(new King(Alliance.BLACK, 4, false, false));
        // White Layout
        builder.setPiece(new Bishop(Alliance.WHITE, 0));
        builder.setPiece(new King(Alliance.WHITE, 60, false, false));
        // Set the current player
        builder.setMoveMaker(Alliance.WHITE);
        //build the board
        final Board board = builder.build();
        final Collection<Move> whiteLegals = board.whitePlayer().getLegalMoves();
        final Collection<Move> blackLegals = board.blackPlayer().getLegalMoves();
        assertEquals(board.getPiece(0), board.getPiece(0));
        assertNotNull(board.getPiece(0));
        assertEquals(whiteLegals.size(), 12);
        assertEquals(blackLegals.size(), 5);
        assertTrue(whiteLegals.contains(Move.MoveFactory
                .createMove(board, BoardUtils.INSTANCE.getCoordinateAtPosition("a8"), BoardUtils.INSTANCE.getCoordinateAtPosition("b7"))));
        assertTrue(whiteLegals.contains(Move.MoveFactory
                .createMove(board, BoardUtils.INSTANCE.getCoordinateAtPosition("a8"), BoardUtils.INSTANCE.getCoordinateAtPosition("c6"))));
        assertTrue(whiteLegals.contains(Move.MoveFactory
                .createMove(board, BoardUtils.INSTANCE.getCoordinateAtPosition("a8"), BoardUtils.INSTANCE.getCoordinateAtPosition("d5"))));
        assertTrue(whiteLegals.contains(Move.MoveFactory
                .createMove(board, BoardUtils.INSTANCE.getCoordinateAtPosition("a8"), BoardUtils.INSTANCE.getCoordinateAtPosition("e4"))));
        assertTrue(whiteLegals.contains(Move.MoveFactory
                .createMove(board, BoardUtils.INSTANCE.getCoordinateAtPosition("a8"), BoardUtils.INSTANCE.getCoordinateAtPosition("f3"))));
        assertTrue(whiteLegals.contains(Move.MoveFactory
                .createMove(board, BoardUtils.INSTANCE.getCoordinateAtPosition("a8"), BoardUtils.INSTANCE.getCoordinateAtPosition("g2"))));
        assertTrue(whiteLegals.contains(Move.MoveFactory
                .createMove(board, BoardUtils.INSTANCE.getCoordinateAtPosition("a8"), BoardUtils.INSTANCE.getCoordinateAtPosition("h1"))));
    }
  
  @Test
  public void knights(){
	  final Board.Builder builder = new Board.Builder();
      // Black Layout
      builder.setPiece(new King(Alliance.BLACK, 4, false, false));
      // White Layout
      builder.setPiece(new Knight(Alliance.WHITE, 36));
      builder.setPiece(new King(Alliance.WHITE, 60, false, false));
      // Set the current player
      builder.setMoveMaker(Alliance.WHITE);
      final Board board = builder.build();
      final Collection<Move> whiteLegals = board.whitePlayer().getLegalMoves();
      final Collection<Move> blackLegals = board.blackPlayer().getLegalMoves();
      assertEquals(whiteLegals.size(), 18);
      assertEquals(blackLegals.size(), 5);
      assertTrue(whiteLegals.contains(Move.MoveFactory
              .createMove(board, BoardUtils.INSTANCE.getCoordinateAtPosition("e4"), BoardUtils.INSTANCE.getCoordinateAtPosition("e8"))));
      assertTrue(whiteLegals.contains(Move.MoveFactory
              .createMove(board, BoardUtils.INSTANCE.getCoordinateAtPosition("e4"), BoardUtils.INSTANCE.getCoordinateAtPosition("e7"))));
      assertTrue(whiteLegals.contains(Move.MoveFactory
              .createMove(board, BoardUtils.INSTANCE.getCoordinateAtPosition("e4"), BoardUtils.INSTANCE.getCoordinateAtPosition("e6"))));
      assertTrue(whiteLegals.contains(Move.MoveFactory
              .createMove(board, BoardUtils.INSTANCE.getCoordinateAtPosition("e4"), BoardUtils.INSTANCE.getCoordinateAtPosition("e5"))));
      assertTrue(whiteLegals.contains(Move.MoveFactory
              .createMove(board, BoardUtils.INSTANCE.getCoordinateAtPosition("e4"), BoardUtils.INSTANCE.getCoordinateAtPosition("e3"))));
      assertTrue(whiteLegals.contains(Move.MoveFactory
              .createMove(board, BoardUtils.INSTANCE.getCoordinateAtPosition("e4"), BoardUtils.INSTANCE.getCoordinateAtPosition("e2"))));
      assertTrue(whiteLegals.contains(Move.MoveFactory
              .createMove(board, BoardUtils.INSTANCE.getCoordinateAtPosition("e4"), BoardUtils.INSTANCE.getCoordinateAtPosition("a4"))));
      assertTrue(whiteLegals.contains(Move.MoveFactory
              .createMove(board, BoardUtils.INSTANCE.getCoordinateAtPosition("e4"), BoardUtils.INSTANCE.getCoordinateAtPosition("b4"))));
      assertTrue(whiteLegals.contains(Move.MoveFactory
              .createMove(board, BoardUtils.INSTANCE.getCoordinateAtPosition("e4"), BoardUtils.INSTANCE.getCoordinateAtPosition("c4"))));
      assertTrue(whiteLegals.contains(Move.MoveFactory
              .createMove(board, BoardUtils.INSTANCE.getCoordinateAtPosition("e4"), BoardUtils.INSTANCE.getCoordinateAtPosition("d4"))));
      assertTrue(whiteLegals.contains(Move.MoveFactory
              .createMove(board, BoardUtils.INSTANCE.getCoordinateAtPosition("e4"), BoardUtils.INSTANCE.getCoordinateAtPosition("f4"))));
      assertTrue(whiteLegals.contains(Move.MoveFactory
              .createMove(board, BoardUtils.INSTANCE.getCoordinateAtPosition("e4"), BoardUtils.INSTANCE.getCoordinateAtPosition("g4"))));
      assertTrue(whiteLegals.contains(Move.MoveFactory
              .createMove(board, BoardUtils.INSTANCE.getCoordinateAtPosition("e4"), BoardUtils.INSTANCE.getCoordinateAtPosition("h4"))));
  }
  
  @Test
  public void pawns(){
	  final Board.Builder builder = new Board.Builder();
      // Black Layout
      builder.setPiece(new King(Alliance.BLACK, 4, false, false));
      // White Layout
      builder.setPiece(new Pawn(Alliance.WHITE, 36));
      builder.setPiece(new King(Alliance.WHITE, 60, false, false));
      // Set the current player
      builder.setMoveMaker(Alliance.WHITE);
      final Board board = builder.build();
      final Collection<Move> whiteLegals = board.whitePlayer().getLegalMoves();
      final Collection<Move> blackLegals = board.blackPlayer().getLegalMoves();
      assertEquals(whiteLegals.size(), 18);
      assertEquals(blackLegals.size(), 5);
      assertTrue(whiteLegals.contains(Move.MoveFactory
              .createMove(board, BoardUtils.INSTANCE.getCoordinateAtPosition("e4"), BoardUtils.INSTANCE.getCoordinateAtPosition("e8"))));
      assertTrue(whiteLegals.contains(Move.MoveFactory
              .createMove(board, BoardUtils.INSTANCE.getCoordinateAtPosition("e4"), BoardUtils.INSTANCE.getCoordinateAtPosition("e7"))));
      assertTrue(whiteLegals.contains(Move.MoveFactory
              .createMove(board, BoardUtils.INSTANCE.getCoordinateAtPosition("e4"), BoardUtils.INSTANCE.getCoordinateAtPosition("e6"))));
      assertTrue(whiteLegals.contains(Move.MoveFactory
              .createMove(board, BoardUtils.INSTANCE.getCoordinateAtPosition("e4"), BoardUtils.INSTANCE.getCoordinateAtPosition("e5"))));
      assertTrue(whiteLegals.contains(Move.MoveFactory
              .createMove(board, BoardUtils.INSTANCE.getCoordinateAtPosition("e4"), BoardUtils.INSTANCE.getCoordinateAtPosition("e3"))));
      assertTrue(whiteLegals.contains(Move.MoveFactory
              .createMove(board, BoardUtils.INSTANCE.getCoordinateAtPosition("e4"), BoardUtils.INSTANCE.getCoordinateAtPosition("e2"))));
      assertTrue(whiteLegals.contains(Move.MoveFactory
              .createMove(board, BoardUtils.INSTANCE.getCoordinateAtPosition("e4"), BoardUtils.INSTANCE.getCoordinateAtPosition("a4"))));
      assertTrue(whiteLegals.contains(Move.MoveFactory
              .createMove(board, BoardUtils.INSTANCE.getCoordinateAtPosition("e4"), BoardUtils.INSTANCE.getCoordinateAtPosition("b4"))));
      assertTrue(whiteLegals.contains(Move.MoveFactory
              .createMove(board, BoardUtils.INSTANCE.getCoordinateAtPosition("e4"), BoardUtils.INSTANCE.getCoordinateAtPosition("c4"))));
      assertTrue(whiteLegals.contains(Move.MoveFactory
              .createMove(board, BoardUtils.INSTANCE.getCoordinateAtPosition("e4"), BoardUtils.INSTANCE.getCoordinateAtPosition("d4"))));
      assertTrue(whiteLegals.contains(Move.MoveFactory
              .createMove(board, BoardUtils.INSTANCE.getCoordinateAtPosition("e4"), BoardUtils.INSTANCE.getCoordinateAtPosition("f4"))));
      assertTrue(whiteLegals.contains(Move.MoveFactory
              .createMove(board, BoardUtils.INSTANCE.getCoordinateAtPosition("e4"), BoardUtils.INSTANCE.getCoordinateAtPosition("g4"))));
      assertTrue(whiteLegals.contains(Move.MoveFactory
              .createMove(board, BoardUtils.INSTANCE.getCoordinateAtPosition("e4"), BoardUtils.INSTANCE.getCoordinateAtPosition("h4"))));
  }
  
  @Test
  public void boundries(){
    
  }
  
  @Test
  public void piecehasbeeneaten(){
    
  }
	/**
	 * Test to make sure pawns move properly.
	 * 
	 * Note: White pawns move up, Black pawns move down.
	 */
	@Test
	public void testPawnMovements(){
		Pawn testPawn = new Pawn(standardBoard, WHITE, 3, 3);
		
		//One step
		assertTrue(testPawn.canMoveTo(2, 3));
		//Two step first move
		assertTrue(testPawn.canMoveTo(1, 3));
		//Three step
		assertFalse(testPawn.canMoveTo(0, 3));
		//Back step
		assertFalse(testPawn.canMoveTo(4, 3));
		
		// Diagonal without enemies
		assertFalse(testPawn.canMoveTo(2, 2));
		
		// Diagonal with enemies
		Pawn testPawn2 = new Pawn(standardBoard, BLACK, 2, 2);
		assertTrue(testPawn.canMoveTo(2, 2));
		
		// One step, black
		assertTrue(testPawn2.canMoveTo(3, 2));
		// back step, black
		assertFalse(testPawn2.canMoveTo(1, 2));
		
		//Invalid move, out-of-bounds
		testPawn.moveTo(0, 0);
		assertFalse(testPawn.canMoveTo(-1, 0));
		
		// Invalid move, partner in front
		testPawn.moveTo(3, 3);
		Pawn testPawn3 = new Pawn(standardBoard, WHITE, 2, 3);
		assertFalse(testPawn.canMoveTo(2, 3));
		
		// Two step, already moved
		testPawn3.moveTo(5, 5);
		assertFalse(testPawn3.canMoveTo(3, 5));
	}
	
	/**
	 * Test to make sure knight moves properly.
	 */
	@Test
	public void testKnightMovements(){
		Knight testKnight = new Knight(standardBoard, WHITE, 3, 3);
		
		// All 8 valid movements
		assertTrue(testKnight.canMoveTo(1,2));
		assertTrue(testKnight.canMoveTo(1,4));
		assertTrue(testKnight.canMoveTo(5,2));
		assertTrue(testKnight.canMoveTo(5,4));
		assertTrue(testKnight.canMoveTo(2,1));
		assertTrue(testKnight.canMoveTo(4,1));
		assertTrue(testKnight.canMoveTo(2,5));
		assertTrue(testKnight.canMoveTo(4,5));
		
		// same spot
		assertFalse(testKnight.canMoveTo(3, 3));
		
		// empty spot, but invalid movement
		assertFalse(testKnight.canMoveTo(4, 4));
		
		// out of bounds
		testKnight.moveTo(1, 1);
		assertFalse(testKnight.canMoveTo(-1, 0));
		
		// ally spot
		assertTrue(testKnight.canMoveTo(3, 2));
		Pawn testPawn = new Pawn(standardBoard, WHITE, 3, 2);
		assertFalse(testKnight.canMoveTo(3, 2));
	}
	
	/**
	 * Test to make sure rook moves properly.
	 */
	@Test
	public void testRookMovements(){
		Rook testRook = new Rook(standardBoard, WHITE, 1, 1);
		
		straightMovementCheck(testRook);
	}
	
	/**
	 * Test to make sure bishop moves properly.
	 */
	@Test
	public void testBishopMovements(){
		Bishop testBishop = new Bishop(standardBoard, WHITE, 1, 1);
		
		diagonalMovementCheck(testBishop);
	}
	
	/**
	 * Test to verify the Queen moves properly
	 */
	@Test
	public void testQueenMovements(){
		Queen testQueen = new Queen(standardBoard, WHITE, 1, 1);
		
		// Test straight
		straightMovementCheck(testQueen);
		
		// Test diagonal
		diagonalMovementCheck(testQueen);
	}
	
	/**
	 * Helper function for testing if a piece that moves
	 * diagonally works properly (bishops, queen)
	 * @param testPiece - the test piece being tested
	 */
	private void diagonalMovementCheck(Piece testPiece){
		testPiece.moveTo(1, 1);
		assertTrue(testPiece.canMoveTo(3, 3));
		assertTrue(testPiece.canMoveTo(0, 2));
		
		// Units in the way
		Pawn testEnemyPawn = new Pawn(standardBoard, BLACK, 2, 2);
		Pawn testAllyPawn = new Pawn(standardBoard, WHITE, 2, 0);
		
		assertTrue(testPiece.canMoveTo(2, 2));
		assertFalse(testPiece.canMoveTo(3, 3));
		assertFalse(testPiece.canMoveTo(2, 0));
		
		// Out of Bounds
		assertFalse(testPiece.canMoveTo(-1, -1));
	}
	
	/**
	 * Helper function for testing if a piece that moves
	 * straight works properly (rook, queen)
	 * @param testPiece - the test piece being tested
	 */
	private void straightMovementCheck(Piece testPiece){
		testPiece.moveTo(1, 1);
		assertTrue(testPiece.canMoveTo(5, 1));
		assertTrue(testPiece.canMoveTo(1, 4));
		
		// Units in the way
		Pawn testEnemyPawn = new Pawn(standardBoard, BLACK, 2, 1);
		Pawn testAllyPawn = new Pawn(standardBoard, WHITE, 1, 1);
		
		assertTrue(testPiece.canMoveTo(2, 1));
		assertFalse(testPiece.canMoveTo(3, 1));
		assertFalse(testPiece.canMoveTo(1, 1));
		
		// Out of Bounds
		assertFalse(testPiece.canMoveTo(1, -1));
	}
	
	/**
	 * Test to verify the King moves properly
	 */
	@Test
	public void testKingMovements(){
		King testKing = new King(standardBoard, WHITE, 1, 1);
		
		// Test all 8 valid spots
		assertTrue(testKing.canMoveTo(0, 0));
		assertTrue(testKing.canMoveTo(0, 1));
		assertTrue(testKing.canMoveTo(0, 2));
		assertTrue(testKing.canMoveTo(1, 0));
		assertTrue(testKing.canMoveTo(1, 2));
		assertTrue(testKing.canMoveTo(2, 0));
		assertTrue(testKing.canMoveTo(2, 1));
		assertTrue(testKing.canMoveTo(2, 2));
		
		// Test same spot
		assertFalse(testKing.canMoveTo(1,1));
		
		// Test too many steps
		assertFalse(testKing.canMoveTo(3, 1));
		
		// Test out of bounds
		testKing.moveTo(0, 0);
		assertFalse(testKing.canMoveTo(-1, 0));
		
		// Ally unit in the way
		assertTrue(testKing.canMoveTo(1, 1));
		Pawn testPawn = new Pawn(standardBoard, WHITE, 1, 1);
		assertFalse(testKing.canMoveTo(1, 1));
	}
}
