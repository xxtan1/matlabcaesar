function coded = caesar(str, shift)
num = str + shift;

for i=1:length(num)
    while num(i) < 32
        num(i)= num(i) +126 -32 + 1; %which is +95, but I wrote it like this to be easier to imagine
    end
    while num(i) > 126
        num(i) = num(i) -126 + 32 -1; &which is equal to -95
    end
end
coded = char(num)
