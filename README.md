- š Hi, Iām @LilianaKor
- š Iām interested in ...
- š± Iām currently learning ...
- šļø Iām looking to collaborate on ...
- š« How to reach me ...

<!---
LilianaKor/LilianaKor is a āØ special āØ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

@Test
    public void testArrays() {
        int[] arrayOfNumbers = {1, 2, 3 , 4, 5, 6};

        String firstCar = "Volvo";
        String secondCar = "Toyota";
        String thirdCar = "Tesla";
        
        String[] garage = {firstCar, secondCar, thirdCar};

        for(int i = 0; i < garage.length; i++){
            System.out.println("Car" + "[" + i + "]=" + garage[i]);
        }

        for(String eachCar : garage){
            System.out.println("Car:" + eachCar);
        }
    }
