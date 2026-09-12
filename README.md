
def find_common_items(first, second):
    return sorted(set(first) & set(second))


if __name__ == "__main__":
    list_a = [2, 4, 6, 8, 10]
    list_b = [1, 4, 7, 8, 12]

    print("First list:", list_a)
    print("Second list:", list_b)
    print("Common items:", find_common_items(list_a, list_b))
