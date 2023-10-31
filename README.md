- 👋 Hi, I’m @ajyan21
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
ajyan21/ajyan21 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
import time

def typing_test():
    sentence = "The quick brown fox jumps over the lazy dog."
    print("Type the following sentence:")
    print(sentence)

    input("Press Enter when you're ready to start...")
    
    start_time = time.time()
    user_input = input("Type the sentence above: ")
    end_time = time.time()

    elapsed_time = end_time - start_time
    words_typed = len(user_input.split())
    typing_speed = words_typed / (elapsed_time / 60)  # Words per minute
    
    print(f"\nTime taken: {elapsed_time:.2f} seconds")
    print(f"Words typed: {words_typed}")
    print(f"Typing speed: {typing_speed:.2f} words per minute")

if __name__ == "__main__":
    typing_test()

