# Python code
#
me = 0

def on_button_pressed_a():
  pins.servo_write_pin(AnalogPin.P0, 45)
input.on_button_pressed(Button.A, on_button_pressed_a)

def on_button_pressed_b():
  pins.servo_write_pin(AnalogPin.P0, -45)
input.on_button_pressed(Button.B, on_button_pressed_b)
