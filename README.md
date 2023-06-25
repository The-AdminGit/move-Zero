# move-Zero

code logic is here

int i = 0, j = 0;
    while (i < nums.length) {
        if (nums[i] != 0) {
            int temp = nums[i];
            nums[i] = nums[j];
            nums[j] = temp;
            j++;
        }
        i++;
    }
