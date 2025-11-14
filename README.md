# Function-Modifier-Draft-10
function applyModifier(
        uint _base,
        int _modifier
    ) external pure override returns (uint) {
        return uint(int256(_base) + _modifier);
    }
