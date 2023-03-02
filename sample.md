'''
export describe("calculate", function() {
it("should return sum of two numbers", function() {
expect(calculate(1, 2, "+")).toEqual(3);
});
it("should return difference of two numbers", function() {
expect(calculate(1, 2, "-")).toEqual(-1);
});
it("should return product of two numbers", function() {
expect(calculate(1, 2, "\*")).toEqual(2);
});
it("should return quotient of two numbers", function() {
expect(calculate(1, 2, "/")).toEqual(0.5);
});
it("should return Invalid operator", function() {
expect(calculate(1, 2, "^")).toEqual("Invalid operator");
});
});
'''
