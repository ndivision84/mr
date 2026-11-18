# Mach Rider

Порт/разработка для macOS 12.7.6 (Intel, x86_64).

## Стек
- C++20
- CMake >= 3.20
- SDL3 (Homebrew)

## Сборка
mkdir -p build && cd build
cmake -DCMAKE_BUILD_TYPE=Release ..
cmake --build .
./mr

## Требования
- macOS 12.7.6 (Monterey) Intel
- Homebrew: brew install cmake sdl3

## Структура
mr/
├── CMakeLists.txt
├── src/          # Исходный код
├── assets/       # Ресурсы
├── docs/         # Документация, RE-заметки
├── tools/        # Скрипты, утилиты
└── README.md

## Лицензия
© Nordic Division · CC BY-NC-SA 4.0 · Non-commercial
