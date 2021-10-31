public static int randomoffset(int min, int max) {
  int n;
  n = (int) (Math.random() * ((max - min) + 1) + min);
  return n;
}
