instalar mlx42 codam --- https://github.com/codam-coding-college/MLX42

cd MLX42
cmake -B build
cmake --build build

compilar con ->
gcc -O3 -ffast-math cub3d.c -o cub3d \
    -I./MLX42/include \
    -L./MLX42/build -lmlx42 \
    -lglfw -ldl -lm -lX11 -lXrandr -lXi -lXcursor -lXinerama -lGL
