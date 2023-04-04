# Minimum_Steps_Required-
java, problem, solution , Array , Problem of the day , geeksforGeek , Minimum steps required 


       char c = str.charAt(0);
        int ans = 0;
        boolean flag = true;
        for(int i=1; i<str.length(); i++){
            if(str.charAt(i) == c) {
                if(!flag){
                    ans++;
                }
                flag = true;
                continue;
            }
            else{
                if(i == str.length() -1)ans++;
                flag = false;
            }
        }
        return ++ans;
        	}
      }
