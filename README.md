# Assignment-5
Doing Math
> A <- matrix(1:100, nrow = 10)
> B <- matrix(1:1000, nrow = 10)
> t_A <- t(A)
> t_B <- t(B)
> a <- 1:10
> b <- 1:10
> A_times_a <- A %*% a
> B_times_b <- t(B) %*% b
> a <- rep(1:10, each = 10)
> b <- rep(1:10, times = 10)
> C <- A %*% B
> S <- matrix(2:5, nrow = 2)
> S_det <- det(S)
> S_inverse <- if (S_det != 0) solve(S) else NULL
> print("A times a:")
[1] "A times a:"
> print(A_times_a)
> print("B times b:")
[1] "B times b:"
> print(B_times_b)
> print("Matrix multiplication of A and B:")
[1] "Matrix multiplication of A and B:"
> print(C)
> print("Determinant of matrix S:")
[1] "Determinant of matrix S:"
> print(S_det)
> print("Inverse of matrix S:")
[1] "Inverse of matrix S:"
> print(S_inverse)
