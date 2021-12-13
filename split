class CheapStocks {

    public String getCheapStocks(String[] stocks){
        String str = ""; // Создаем пустую строку
        for (int i = 0; i < stocks.length; i++) {
            String [] strings = stocks[i].split(" "); // Создаем массив с длиной stocks[i].split()
            int number = Integer.parseInt(strings[1]); //Создаем int в него засовываем второй элемент массив и парсим в int
            if (number < 200){  // И так понятно 
                str = str + strings[0] + " ";  //Вывод название строк 
            }
        }return str;
    }

    public static void main(String[] args) {

    }
}
