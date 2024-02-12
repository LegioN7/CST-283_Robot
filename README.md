// Define an abstact data type for robot.
// (This is very broad and you have a lot of latitude in your answer.)

// * Consider the data attributes of the robot. What *data* would it store? What information might be available via sensors?
// * Consider the actions programmed for the robot. What *functions* would it recognize?

// The robot would be the abstract data type here with the underlaying features, and requirements of the robot defined.

public abstract class Robot
{
  public double BatteryStatus;
  public double IntegrityCheck;
  public int SerialNumber;
  public int HourUptime;
  public int YearCreated;
  public String RobotType;
}

public class RobotSensors extends Robot
{
  public int LeftEyeSensor;
  public int RightEyeSensor;
}

public class RobotLimbs extends Robot
{
  private int LeftLegSensorPosition;
  private int RightLegSensorPosition;
  private int LeftArmSensorPosition;
  private int RightArmSensorPosition;
  private double HeadDegreePosition;
}

@Override
public int BatteryPercentage

public int IntegrityStatus

public int SensorView? (capturing what each sensor sees)

public int LimbDegree (capturing how to move the arms and legs?)

