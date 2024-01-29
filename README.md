# AES MixColumns Transformation

This Python script performs the MixColumns transformation in the Advanced Encryption Standard (AES) algorithm. The MixColumns transformation is a crucial step for confounding and diffusing data.

## How to Use

1. Run the script and input the matrix size (in this case, `4` for a 4x4 matrix).
2. Input the matrix elements, separating each row by spaces and each element within a row by spaces.
3. The script will display the input matrix.
4. The MixColumns transformation and its inverse will be applied to each column, and the results will be shown.
5. The final matrix, along with the MixColumns and inverse MixColumns results, will be displayed using Matplotlib.

## Example Input:

```
4
1 2 3 4
5 6 7 8
9 10 11 12
13 14 15 16
```

### Output:

```plaintext
Input Matrix:
[[1, 2, 3, 4], [5, 6, 7, 8], [9, 10, 11, 12], [13, 14, 15, 16]]

Mixed: [7, 14, 17, 28]
Inverse mixed: [77, 112, 83, 106]

Mixed: [35, 34, 37, 56]
Inverse mixed: [241, 180, 207, 150]

Mixed: [63, 70, 73, 68]
Inverse mixed: [243, 69, 109, 175]

Mixed: [75, 74, 77, 112]
Inverse mixed: [226, 103, 156, 37]
```

## Note

- Ensure that Matplotlib is installed by running:

```bash
pip install matplotlib
```

- This code is designed for educational purposes to understand the AES algorithm and is not recommended for use in actual security applications.

## Reference Resources

- [AES - MixColumns Transformation](https://en.wikipedia.org/wiki/Rijndael_MixColumns)
