print("DC GENERATOR EMF CALCULATOR")
print("-" * 35)

P = int(input("Enter number of poles: "))
phi = float(input("Enter flux per pole (Wb): "))
Z = int(input("Enter total number of armature conductors: "))
N = float(input("Enter speed (RPM): "))
A = int(input("Enter number of parallel paths: "))

E = (P * phi * Z * N) / (60 * A)

print("\nRESULT")
print("Number of poles       :", P)
print("Flux per pole         :", phi, "Wb")
print("Armature conductors   :", Z)
print("Speed                 :", N, "RPM")
print("Parallel paths        :", A)
print("Generated EMF         :", round(E, 2), "V")

if E > 0:
    print("Generator is producing voltage.")
else:
    print("Invalid input.")# Dc-generator-emf-
