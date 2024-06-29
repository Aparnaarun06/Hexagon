def print_hexagon_pattern(rows, cols):
    hex_top = "  __  "
    hex_mid_upper = " /    \\ "
    hex_mid_lower = "/      \\"
    hex_bottom_upper = "\\      /"
    hex_bottom_lower = " \\__/ "

    for row in range(rows):
        if row % 2 == 0:
            
            print(" " + (hex_top + " ") * cols)
            print(" " + (hex_mid_upper + " ") * cols)
            print(" " + (hex_mid_lower + " ") * cols)
            print(" " + (hex_bottom_upper + " ") * cols)
            print(" " + (hex_bottom_lower + " ") * cols)
        else:
           
            print((hex_top + " ") * cols)
            print((hex_mid_upper + " ") * cols)
            print((hex_mid_lower + " ") * cols)
            print((hex_bottom_upper + " ") * cols)
            print((hex_bottom_lower + " ") * cols)


print("Inputs: 4 7")
print_hexagon_pattern(4, 7)

print("Inputs: 3 5")
print_hexagon_pattern(3, 5)
