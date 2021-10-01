# Gade-6112-Task-1
 public abstract class Tile
    {
        protected int X;
        public int GetX() { return X; }

        protected int Y;
        public int GetY() { return Y; }


        public enum TileType { HERO, ENEMY, GOLD, WEAPON };

        public Tile(int x, int y)
        {
            X = x;
            Y = y;
        }



    }
