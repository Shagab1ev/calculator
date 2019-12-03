public void plus(View v){
        EditText number1 = (EditText)(findViewById(R.id.num1));
        EditText number2 = (EditText)(findViewById(R.id.num2));
        TextView res = (TextView)(findViewById(R.id.Result));
        int num1 = Integer.parseInt(number1.getText().toString());
        int num2 = Integer.parseInt(number2.getText().toString());
        int resSum = num1+num2;
        res.setText(Integer.toString(resSum));
    }
    public void minus(View v1){
        EditText number1 = (EditText)(findViewById(R.id.num1));
        EditText number2 = (EditText)(findViewById(R.id.num2));
        TextView res = (TextView)(findViewById(R.id.Result));
        int num1 = Integer.parseInt(number1.getText().toString());
        int num2 = Integer.parseInt(number2.getText().toString());
        int resSum = num1-num2;
        res.setText(Integer.toString(resSum));
    }
