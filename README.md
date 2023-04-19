# Arraylist-and-generics-min-max


//To find min and max numbers, using ArrayList and generics:

class Array {

    public static void main(String... test) {

        ArrayList<Integer> a=new ArrayList<>(10);

        a.add(1);

        a.add(122);

        a.add(5765);

        int max=a.get(0);

        int min=a.get(0);

        for(int i=0;i<a.size();i++){

            if(max>a.get(i)){

                max=a.get(i);

            }

            else if(min<a.get(i)){

                min=a.get(i);

            }

        }

        System.out.println(" The maximum number in the array is : "+ max);

        System.out.println(" The minimum number in the array is : "+min);

        }

    }

    /*

    The maximum number in the array is : 1

    The minimum number in the array is : 5765

     */
