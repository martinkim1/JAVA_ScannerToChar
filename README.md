# JAVA_ScannerToChar
자바 Scanner는 문자를 입력받는 기능이 없다.
즉, Scanner.next()로 문자열을 입력받은 다음, String.charAt(0)으로 첫번째 문자를 꺼내오면 된다.

Scanner s = new Scanner(System.in);
char input = sc.next().charAt(0);
