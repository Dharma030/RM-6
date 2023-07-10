# RM-6

Write a “person” class to hold all the details.
****

class Person {
  private name: "DHARMA";
  private age: 22;
  private address: "ADDRESS";

  constructor(name: string, age: number, address: string) {
    this.name = name;
    this.age = age;
    this.address = address;
  }

  getName(): string {
    return this.name;
  }

  getAge(): number {
    return this.age;
  }

  getAddress(): string {
    return this.address;
  }
}

write a class to calculate the uber price.
****

class UberPriceCalculator {
  private baseFare: number;
  private costPerKilometer: number;

  constructor(baseFare: number, costPerKilometer: number) {
    this.baseFare = baseFare;
    this.costPerKilometer = costPerKilometer;
  }

  calculatePrice(distance: number): number {
    return this.baseFare + this.costPerKilometer * distance;
  }
}

