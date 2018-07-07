//# twosum
//Given an array of integers, return indices of the two numbers such that they add up to a specific target.  You may assume that each input would have exactly one solution, and you may not use the same element twice.
static void Main(string[] args)
        {
            int[] nums = { 1, 2, 3, 4, 5, 6, 7, 9, 0 };
            int target = 9;


            for (int i = 0; i < nums.Length; i++)
            {
                for (int j = i; j < nums.Length; j++)
                {
                    if (nums[i] + nums[j] == target)
                    {
                        if (nums[i] != nums[j])
                        {
                            Console.WriteLine("{0}, {1}", i, j);
                        }
                    }
                    else

                        continue;



                }
            }
                         Console.ReadKey();
        }
    }
