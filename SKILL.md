# jdk.base Skill

Use this skill to work with Norm module `jdk.base` version 1. Use only declarations listed below.

## `jdk.base`

### `BigDecimal`

```norm
class BigDecimal implements Serializable
```

#### `BigDecimal`

```norm
BigDecimal(__JarBindingToken token)
```

#### `abs`

```norm
BigDecimal? abs()
```

#### `abs`

```norm
BigDecimal? abs(MathContext? arg0)
```

#### `add`

```norm
BigDecimal? add(BigDecimal? arg0)
```

#### `add`

```norm
BigDecimal? add(BigDecimal? arg0, MathContext? arg1)
```

#### `compareToJavaBigDecimalJavabe9dae04`

```norm
Integer compareToJavaBigDecimalJavabe9dae04(BigDecimal? arg0)
```

#### `compareToJavaBigDecimalJavaf50fc317`

```norm
Integer compareToJavaBigDecimalJavaf50fc317(BigDecimal? arg0)
```

#### `divide`

```norm
BigDecimal? divide(BigDecimal? arg0)
```

#### `divide`

```norm
BigDecimal? divide(BigDecimal? arg0, Integer arg1, RoundingMode? arg2)
```

#### `divide`

```norm
BigDecimal? divide(BigDecimal? arg0, MathContext? arg1)
```

#### `divide`

```norm
BigDecimal? divide(BigDecimal? arg0, RoundingMode? arg1)
```

#### `multiply`

```norm
BigDecimal? multiply(BigDecimal? arg0)
```

#### `multiply`

```norm
BigDecimal? multiply(BigDecimal? arg0, MathContext? arg1)
```

#### `negate`

```norm
BigDecimal? negate()
```

#### `negate`

```norm
BigDecimal? negate(MathContext? arg0)
```

#### `scale`

```norm
Integer scale()
```

#### `setScale`

```norm
BigDecimal? setScale(Integer arg0)
```

#### `setScale`

```norm
BigDecimal? setScale(Integer arg0, RoundingMode? arg1)
```

#### `signum`

```norm
Integer signum()
```

#### `subtract`

```norm
BigDecimal? subtract(BigDecimal? arg0)
```

#### `subtract`

```norm
BigDecimal? subtract(BigDecimal? arg0, MathContext? arg1)
```

#### `toPlainString`

```norm
String? toPlainString()
```

#### `toString`

```norm
String? toString()
```

### `bigDecimalNew`

```norm
BigDecimal bigDecimalNew(String? arg0)
```

## `jdk.base`

### `DayOfWeek`

```norm
enum DayOfWeek
```

#### `FRIDAY`

```norm
FRIDAY
```

#### `MONDAY`

```norm
MONDAY
```

#### `SATURDAY`

```norm
SATURDAY
```

#### `SUNDAY`

```norm
SUNDAY
```

#### `THURSDAY`

```norm
THURSDAY
```

#### `TUESDAY`

```norm
TUESDAY
```

#### `WEDNESDAY`

```norm
WEDNESDAY
```

### `dayOfWeekGetValue`

```norm
Integer dayOfWeekGetValue(DayOfWeek receiver)
```

### `dayOfWeekOf`

```norm
DayOfWeek? dayOfWeekOf(Integer arg0)
```

## `jdk.base`

### `LocalDate`

```norm
class LocalDate implements Temporal, TemporalAdjuster, ChronoLocalDate, Serializable
```

#### `LocalDate`

```norm
LocalDate(__JarBindingToken token)
```

#### `getDayOfMonth`

```norm
Integer getDayOfMonth()
```

#### `getDayOfWeek`

```norm
DayOfWeek? getDayOfWeek()
```

#### `getMonthValue`

```norm
Integer getMonthValue()
```

#### `getYear`

```norm
Integer getYear()
```

#### `isLeapYear`

```norm
Boolean isLeapYear()
```

#### `lengthOfMonth`

```norm
Integer lengthOfMonth()
```

#### `minusDays`

```norm
LocalDate? minusDays(Long arg0)
```

#### `minusMonths`

```norm
LocalDate? minusMonths(Long arg0)
```

#### `plusDays`

```norm
LocalDate? plusDays(Long arg0)
```

#### `plusMonths`

```norm
LocalDate? plusMonths(Long arg0)
```

#### `toEpochDay`

```norm
Long toEpochDay()
```

#### `toString`

```norm
String? toString()
```

### `localDateNow`

```norm
LocalDate? localDateNow()
```

### `localDateNow`

```norm
LocalDate? localDateNow(Clock? arg0)
```

### `localDateNow`

```norm
LocalDate? localDateNow(ZoneId? arg0)
```

### `localDateOf`

```norm
LocalDate? localDateOf(Integer arg0, Integer arg1, Integer arg2)
```

### `localDateOf`

```norm
LocalDate? localDateOf(Integer arg0, Month? arg1, Integer arg2)
```

### `localDateOfEpochDay`

```norm
LocalDate? localDateOfEpochDay(Long arg0)
```

### `localDateParse`

```norm
LocalDate? localDateParse(String? arg0)
```

### `localDateParse`

```norm
LocalDate? localDateParse(String? arg0, DateTimeFormatter? arg1)
```

## `jdk.base`

### `LocalTime`

```norm
class LocalTime implements Temporal, TemporalAdjuster, Serializable
```

#### `LocalTime`

```norm
LocalTime(__JarBindingToken token)
```

#### `getHour`

```norm
Integer getHour()
```

#### `getMinute`

```norm
Integer getMinute()
```

#### `getNano`

```norm
Integer getNano()
```

#### `getSecond`

```norm
Integer getSecond()
```

#### `plusHours`

```norm
LocalTime? plusHours(Long arg0)
```

#### `plusMinutes`

```norm
LocalTime? plusMinutes(Long arg0)
```

#### `plusSeconds`

```norm
LocalTime? plusSeconds(Long arg0)
```

#### `toSecondOfDay`

```norm
Integer toSecondOfDay()
```

#### `toString`

```norm
String? toString()
```

### `localTimeNow`

```norm
LocalTime? localTimeNow()
```

### `localTimeNow`

```norm
LocalTime? localTimeNow(Clock? arg0)
```

### `localTimeNow`

```norm
LocalTime? localTimeNow(ZoneId? arg0)
```

### `localTimeOf`

```norm
LocalTime? localTimeOf(Integer arg0, Integer arg1)
```

### `localTimeOf`

```norm
LocalTime? localTimeOf(Integer arg0, Integer arg1, Integer arg2)
```

### `localTimeOf`

```norm
LocalTime? localTimeOf(Integer arg0, Integer arg1, Integer arg2, Integer arg3)
```

### `localTimeOfSecondOfDay`

```norm
LocalTime? localTimeOfSecondOfDay(Long arg0)
```

### `localTimeParse`

```norm
LocalTime? localTimeParse(String? arg0)
```

### `localTimeParse`

```norm
LocalTime? localTimeParse(String? arg0, DateTimeFormatter? arg1)
```

## `jdk.base`

### `Locale`

```norm
class Locale implements Cloneable, Serializable
```

#### `Locale`

```norm
Locale(__JarBindingToken token)
```

#### `getCountry`

```norm
String? getCountry()
```

#### `getLanguage`

```norm
String? getLanguage()
```

#### `toLanguageTag`

```norm
String? toLanguageTag()
```

### `localeForLanguageTag`

```norm
Locale? localeForLanguageTag(String? arg0)
```

### `localeGetDefault`

```norm
Locale? localeGetDefault()
```

### `localeGetDefault`

```norm
Locale? localeGetDefault(Locale_Category? arg0)
```

## `jdk.base`

### `MathContext`

```norm
class MathContext implements Serializable
```

#### `MathContext`

```norm
MathContext(__JarBindingToken token)
```

#### `getPrecision`

```norm
Integer getPrecision()
```

#### `getRoundingMode`

```norm
RoundingMode? getRoundingMode()
```

### `mathContextNew`

```norm
MathContext mathContextNew(Integer arg0, RoundingMode? arg1)
```

## `jdk.base`

### `Month`

```norm
enum Month
```

#### `APRIL`

```norm
APRIL
```

#### `AUGUST`

```norm
AUGUST
```

#### `DECEMBER`

```norm
DECEMBER
```

#### `FEBRUARY`

```norm
FEBRUARY
```

#### `JANUARY`

```norm
JANUARY
```

#### `JULY`

```norm
JULY
```

#### `JUNE`

```norm
JUNE
```

#### `MARCH`

```norm
MARCH
```

#### `MAY`

```norm
MAY
```

#### `NOVEMBER`

```norm
NOVEMBER
```

#### `OCTOBER`

```norm
OCTOBER
```

#### `SEPTEMBER`

```norm
SEPTEMBER
```

### `monthGetValue`

```norm
Integer monthGetValue(Month receiver)
```

### `monthOf`

```norm
Month? monthOf(Integer arg0)
```

## `jdk.base`

### `RoundingMode`

```norm
enum RoundingMode
```

#### `CEILING`

```norm
CEILING
```

#### `DOWN`

```norm
DOWN
```

#### `FLOOR`

```norm
FLOOR
```

#### `HALF_DOWN`

```norm
HALF_DOWN
```

#### `HALF_EVEN`

```norm
HALF_EVEN
```

#### `HALF_UP`

```norm
HALF_UP
```

#### `UNNECESSARY`

```norm
UNNECESSARY
```

#### `UP`

```norm
UP
```

## `jdk.base`

### `YearMonth`

```norm
class YearMonth implements Temporal, TemporalAdjuster, Serializable
```

#### `YearMonth`

```norm
YearMonth(__JarBindingToken token)
```

#### `atDay`

```norm
LocalDate? atDay(Integer arg0)
```

#### `getMonthValue`

```norm
Integer getMonthValue()
```

#### `getYear`

```norm
Integer getYear()
```

#### `lengthOfMonth`

```norm
Integer lengthOfMonth()
```

#### `minusMonths`

```norm
YearMonth? minusMonths(Long arg0)
```

#### `plusMonths`

```norm
YearMonth? plusMonths(Long arg0)
```

#### `toString`

```norm
String? toString()
```

### `yearMonthNow`

```norm
YearMonth? yearMonthNow()
```

### `yearMonthNow`

```norm
YearMonth? yearMonthNow(Clock? arg0)
```

### `yearMonthNow`

```norm
YearMonth? yearMonthNow(ZoneId? arg0)
```

### `yearMonthOf`

```norm
YearMonth? yearMonthOf(Integer arg0, Integer arg1)
```

### `yearMonthOf`

```norm
YearMonth? yearMonthOf(Integer arg0, Month? arg1)
```

### `yearMonthParse`

```norm
YearMonth? yearMonthParse(String? arg0)
```

### `yearMonthParse`

```norm
YearMonth? yearMonthParse(String? arg0, DateTimeFormatter? arg1)
```

## `jdk.base.io`

### `Serializable`

```norm
interface Serializable
```

## `jdk.base.lang`

### `Cloneable`

```norm
interface Cloneable
```

## `jdk.base.lang.constant`

### `Constable`

```norm
interface Constable
```

## `jdk.base.time`

### `Clock`

```norm
class Clock implements InstantSource
```

#### `Clock`

```norm
Clock(__JarBindingToken token)
```

## `jdk.base.time`

### `InstantSource`

```norm
interface InstantSource
```

## `jdk.base.time`

### `ZoneId`

```norm
class ZoneId implements Serializable
```

#### `ZoneId`

```norm
ZoneId(__JarBindingToken token)
```

## `jdk.base.time.chrono`

### `ChronoLocalDate`

```norm
interface ChronoLocalDate extends Temporal, TemporalAdjuster
```

## `jdk.base.time.format`

### `DateTimeFormatter`

```norm
class DateTimeFormatter
```

#### `DateTimeFormatter`

```norm
DateTimeFormatter(__JarBindingToken token)
```

## `jdk.base.time.temporal`

### `Temporal`

```norm
interface Temporal extends TemporalAccessor
```

## `jdk.base.time.temporal`

### `TemporalAccessor`

```norm
interface TemporalAccessor
```

## `jdk.base.time.temporal`

### `TemporalAdjuster`

```norm
interface TemporalAdjuster
```

## `jdk.base.util`

### `Locale_Category`

```norm
enum Locale_Category
```

#### `DISPLAY`

```norm
DISPLAY
```

#### `FORMAT`

```norm
FORMAT
```

