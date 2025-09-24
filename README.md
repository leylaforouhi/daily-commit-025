def append_to_file(filename, text):
    with open(filename, "a") as f:
        f.write(text + "\n")

if __name__ == "__main__":
    file_name = "note.txt"
    append_to_file(file_name, "New line added to the file.")
    print(f"A new line was appended to '{file_name}'.")
