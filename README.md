# WIL

1.가운데 글자 가져오기
문제 설명
단어 s의 가운데 글자를 반환하는 함수, solution을 만들어 보세요. 단어의 길이가 짝수라면 가운데 두글자를 반환하면 됩니다.

재한사항
s는 길이가 1 이상, 100이하인 스트링입니다.

입출력 예                                         
  s    	return
"abcde"	 "c"
"qwer"	 "we"


class Solution {
    public String solution(String s) {
        String answer = "";
        return answer;
    }
}

를 풀면.

class Solution {
    public String solution(String s) {
        String answer = "";
        if(s.length()%2==0){             
            answer = s.substring(s.length()/2-1, s.length()/2+1);
        } else{
            answer = s.substring(s.length()/2, s.length()/2+1);
        }
        return answer;
    }
}

//짝수와 홀수인 경우로 나누어정리.짝수면 두글자 홀수면 한글자
//문자열의 길이를 절반으로 나누어 진행

-나의 첫번째 알고리즘.

비슷한 문제풀때 삼항연산자라는것을 찾음.
int a = (피연산자1)?(피연산자2) : (피연산자3)
              true         false
              
 조건식이 true 인 경우 int A라는 변수에 (피연산자1) 이 담기고,  false 인 경우에는 A에 (피연산자3)담기긴다.
 가독성이 빨라짐

  


